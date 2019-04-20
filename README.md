# popUp modal

#### CSS
* pointer-events: none || all
<p>none 被覆盖了 还是能点击</p>
<p>all 被覆盖了 就不能点了

#### 被点击的对象
<p>没有使用 e.target<p>

``` javascript
openModalButtons.forEach(button => {
    button.addEventListener('click', () => {
        const modal = document.getElementById('modal');
        openModal(modal);
    })
})
```