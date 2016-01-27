#position 和布局
position property 的 四个值 <br/>
static;relative;fixed;absolute;<br/>

static<br/>
默认值，对应element不受top等位置property的影响

relative<br/>
相对于element原位置定位

fixed<br/>
相对于viewport定位

absolute<br/>
相对于最近的非static元素父级定位，如果没有则相对于body
同时，width 100%的值好像也取自该父级。