
前端纳米学位街机游戏克隆项目
===============================

学生应该用这个[评审标准](https://review.udacity.com/#!/rubrics/499/view))来自我检查自己提交的代码。 确认自己写的函数要是**面向对象的** -  要么是类函数（就像函数 Player 和 Enemy）要么是类的原型链上的函数比如 Enemy.prototype.checkCollisions ， 在类函数里面或者类的原型链函数里面适当的使用关键词 'this' 来引用调用该函数的对象实例。最后保证你的**readme.md**文件要写明关于如何运行和如何玩你的街机游戏的指引。

关于如何开始这个项目的更详细的指导，可以查阅这份[指南](https://gdgdocs.org/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true)。
游戏加载
初始化创建一个角色的对象，以及一个包含众多虫子对象的数组。
初始化，角色一脚虫子的初始位置，传入不同的速度参数。
游戏规则
玩家通过“↑”、“↓”、“←”、“→”键控制角色移动。
玩家每完成一次按键操作角色向任意一方向移动一定距离，当成功到达河岸时游戏获得胜利。
在过程中如果碰到运动的虫子，则游戏失败返回远点重新开始。