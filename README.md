# 收藏文章内容实现
- 需要注意scroll-view 的高度 ，他的高度只能比显示内容小，才能正常滚动
- 获取关注文章内容的时候，注意聚合操作的顺序，会影响最终返回结果，要先插入 is_likes 字段，才能去筛选这个字段