

## サイドバーサンプル

[sidebar3.html](/sidebar3.html)

サイドバーを画面サイズに応じて可変させる  
ulの高さをブラウザの高さに追従させoverflow-yをつけてスクロールさせた

```
height: calc(100vh - 64px);
overflow-y: scroll;
```

サイドバー自体はflex-growで追従するので、できればその高さに合わせたかったが。