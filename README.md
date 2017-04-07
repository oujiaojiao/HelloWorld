# HelloWorld
<ul id="literature">
										<li><input type="checkbox" />期刊（325922）</li>
										<li><input type="checkbox" />互联网（52623）</li>
										<li><input type="checkbox" />学位论文（526233）</li>
										<li><input type="checkbox" />会议论文（33）</li>
										<li><input type="checkbox" />图书（599）</li>
										<ul id="wenxian_block" style="display:none;margin-top:-11px;">
											<li><input type="checkbox" />期刊（325922）</li>
											<li><input type="checkbox" />互联网（52623）</li>
											<li><input type="checkbox" />学位论文（526233）</li>
											<li><input type="checkbox" />会议论文（33）</li>
											<li><input type="checkbox" />图书（599）</li>
										</ul>
							
									</ul>
									<div id="Block_id" style="background:url(images/db_arrow.png)no-repeat right center;width:173px;height:17px;margin-top:-8px;cursor:pointer;" onclick="Block('Block_id');"></div>
									<div id="None_id" style="background: url(images/db_arrow_up.png)no-repeat right center;width:173px;height:17px;margin-top:-8px;display:none;cursor:pointer;"onclick="Block('None_id');"></div>
									<script>
										function Block(id){
											if(id=="Block_id"){
												document.getElementById("wenxian_block").style.display="block";
												document.getElementById("Block_id").style.display="none";
												document.getElementById("None_id").style.display="block";
											}else if(id=="None_id"){
												document.getElementById("wenxian_block").style.display="none";
												document.getElementById("Block_id").style.display="block";
												document.getElementById("None_id").style.display="none";
											}
											
										}
									</script>
