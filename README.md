# colorful_resume_template

## How to use

```
/* 简历前景色和背景色 */
:root{
   --bg-color:#005BBB;
   --font-color:#FFD500;
}

/* 简历字体 */
@font-face {
font-family: mFont;
src: url('./fonts/北魏楷书字体.ttf');
}
        body{
            font-family:mFont;
            background-color: var(--bg-color);
            color: var(--font-color);
    }
```

## Compressed font

```
npm i font-spider-plus -g
```

```
➜  myresume git:(main) fsp local resume.html
✔ 优化完成

已提取 297 个 mFont 字体：
 ()+-./0123456789:@ABCDEFGHIJLMOPQRSTUVWXabcdefghijklmnoprstuvwxyz|、。一上下不与业个为乐事于云交亦产京人今从他付代令件价任优作使信元全公关其具内写分刘利制前剪力功务动助化北协历原发台司合吉后味命和品团圈土在块坡培境大好如娱学安定实审对导小展工己巴师常平序库度建开式录微志念态思急悉悦成我户扩找承技护拍指据捷授掌插握摄操支收效敏教数文方日时有术机材构析架查栈核框模毕测渐源演熟环理生用的目盲相码研示秉科积移程稳端等管系级线练组织经络统维编网考者而育能自至行视解言计训讲设评试询语课豆跨辑迁运近进通部酷里重钱阿限隆随集面项频题验高， 
生成字体文件：
* /Users/liuyue/wodfan/work/myresume/fonts/北魏楷书字体.ttf,121K (已优化体积：4089K)
```


## sample

![](./sample.png)
