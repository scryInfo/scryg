[中文](./codestyle_html-cn.md)  

# Code Style -- html
[See](https://google.github.io/styleguide/htmlcssguide.html)
## 规则

1. 使用css不使用style
2. 在布局时能不使用具体的数字就不使用
3. 使用flex进行布局
4. 单位使用rem
5. 功能完成，不是在自己电脑上能运行，是要整个项目能正常运行部署
6. 把问题拿出，不要把它遗忘在开发的过程中，在代码中加入 todo 说明，添加到github的issues
7. 先思考后写代码，从命名开始
8. 在对外提供的接口中，统一错误编号及提示
9. 如果要使用使用全局变量，给出足够的理由，因为它很难测试
10. 提交代码的要求， 说明 格式化 编译通过，如果提交编译不通过的代码需要有特别的理由

## Name 

1. 所有源代码文件名，使用小写，加下划线
2. 所有目录文件名，使用小写，加下划线
3. 命名使用有明确函义的英文单词

## 目录文件
1. 

## 代码
1. 左右居中
2. 上下居中
	1. 文字上下居中
		*. line-height == height
	2. div上下居中
3. 图片居中
4. 相对于另一个div2的对齐
	增加一个div1，把需要的内容放在里面，且设置float，这样增加的div1的高度为零就不会占用布局的位置，让增加的div1与div2靠在一起，内容部分使用position: relative。这样就可以实现比较完美的对齐
5. !important 语法 可以覆盖 element.style, 以及 JS 中控制的样式。
6. z-index 会影响触发事件的元素，并不会影响事件机制本身
7. bootstrap navbar里面的下拉菜单 safari 点击空白 不会回收。
8. safari 中 元素是默认不可点击的。
9. 其他
