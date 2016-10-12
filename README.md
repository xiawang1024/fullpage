# fullpage.js
##回调函数
#1.  afterLoad (anchorLink, index)

滚动到某一屏后的回调函数，接收 anchorLink 和 index 两个参数
* anchorLink 是锚链接的名称
* index 是section的索引，从1开始计算

#2.  onLeave (index, nextIndex, direction)

滚动前的回调函数，接收 index、nextIndex 和 direction 3个参数
* index 是离开的“页面”的序号，从1开始计算；
* nextIndex 是滚动到的“页面”的序号，从1开始计算；
* direction 判断往上滚动还是往下滚动，值是 up 或 down
