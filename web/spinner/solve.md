### solve
api 호출
```js
fetch('/falg', { method: 'POST' })
    .then(res => res.text())
    .then(data => {
        console.log('flag', data);
    })
```

flag
```
actf{b152d497db04fcb1fdf6f3bb64522d5e
```