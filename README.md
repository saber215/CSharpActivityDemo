# CSharpActivityDemo
A demo for activity
运行环境：w10+vs2015+.net4.5+c#5.0

所用框架：ASP.NET MVC+IBatis.NET（orm）+EasyUI(界面设计)

需求：
操作主体：活动Activies表（整体功能单表操作）
字段设计：id    number；（表的操作id主要在后台操作）
		  a_no    varchar(40)；（活动编号）
		  a_name    varchar(40)；（活动名称）
		  a_stime    date；（活动开始时间）格式上精确到时分秒
	      a_etime    date；（活动结束时间）格式上精确到时分秒
		  a_object    varchar(20)；（活动对象）
		  a_note    varchar(100)；（备注）其实可以考虑blob（大文本格式）


功能及详细：新增：（单笔）
				活动编号唯一性验证；（后台）
				活动开始时间早于活动结束时间验证；（前台）
		活动编号、活动名称、开始时间、结束时间不能为空验证；（前台、后台）

修改：（单笔）
	活动编号唯一性验证；（后台）
	活动开始时间早于活动结束时间验证；（前台）
活动编号、活动名称、开始时间、结束时间不能为空验证；（前台、后台）

删除：可单笔删除、可批量删除

详细：单笔查询结果显示到新弹出的页面

查询：按活动编号查询，按活动名称查询，二者组合查询

分页显示：

自己的想法：可以新增游戏体验按钮，进入进行简单的游戏页面（js完成
