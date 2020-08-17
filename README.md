# [template-atom](https://github.com/yanhaijing/template-atom)

[template.js](https://github.com/yanhaijing/template.js)的atom插件，[点击这里查看](https://atom.io/packages/language-templatejs)

## Features

- 语法高亮

支持templatejs的模板语法高亮

下面示例如下

```
<h2>我的待办</h2>
<ul>
    <%list.forEach(function(item, index) {%>
        <li>
            <div class="row">
                <div class="col-5 <%=index % 2 ? 'text-secondary' : ''%>">
                    <%=item.text%>
                    <%:=item.text%>
                    <%abc:=item.text%>
                </div>
            </div>
        </li>
    <%})%>
</ul>
<a href="#" class="btn btn-dark add-todo">新增</a>
```

高亮后的效果

![](./img/demo.png)

## CHANGELOG
[CHANGELOG.md](https://github.com/yanhaijing/template-atom/blob/master/CHANGELOG.md)

## TODO
[TODO.md](https://github.com/yanhaijing/template-atom/blob/master/TODO.md)

**Enjoy!**
