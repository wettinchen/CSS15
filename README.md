## CSS Chapter 15
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## CSS Chapter 15
   Quick Concept outline
   中文摘要說明與重點提問

###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Setup & Starter Code Review
        初始設定說明

###  4. Quickest way to apply a grid
        (1)設定 .container 中， display 為 grid
        (2)grid-auto-flow 為 row
        (3)grid-auto-flow 為 column

###  5. grid-template-columns
        將 grid-auto-flow 更換為 grid-template-columns
        (1)修改 grid-template-columns 為 200px 100px 200px
        (2)修改 grid-template-columns 為 2fr 1fr 1fr，fr 為 fraction
        (3)修改 grid-template-columns 為 200px 1fr 1fr
        (4)修改 grid-template-columns 為 repeat(4, 1fr)
        (5)修改 grid-template-columns 為 repeat(2, 1fr 2fr)

###  6. grid-auto-rows
        (1)設定 grid-auto-rows 為 200px
        (2)修改 grid-auto-rows 為 minmax(150px, auto)
        (3)設定 min-height 為 400px，請問目前 div 欄位的列高多少?

###  7. grid-template-rows, grid-auto-columns
        (1)設定 grid-template-rows 為 200px 100px 200px
        (2)修改 grid-template-rows 為 2fr 1fr 1fr，fr 為 fraction
        (3)修改 grid-template-rows 為 200px 1fr 1fr
        (4)修改 grid-template-rows 為 repeat(4, 1fr)
        (5)修改 grid-template-rows 為 repeat(2, 1fr 2fr)
        (6)設定 grid-auto-columns 為 200px
        (7)修改 grid-auto-columns 為 minmax(150px, auto)
        (8)設定 min-width 為 400px，請問目前 div 欄位的欄高多少?

###  8. row-gap, column-gap, gap
        (1)設定 row-gap 為 1em
        (2)設定 column-gap 為 1em
        (3)設定 gap 為 1em
        (4)設定 gap 為 1em 0.5em
        (5)設定 gap 為預設值 1rem

###  9. grid-column-start & end, grid-row-start & end
        (1)設定 .box 的第一個元素 div 1 的顏色為藍色
        (2)設定 grid-column-start 為 1 ，並設定 grid-column-end 為 4，並說明 grid 網格概念。
        (3)設定 grid-row-start 為 1 ，並設定 grid-row-end 為 3，並說明 grid 網格概念。
        
### 10. Viewing your grid in dev tools
        使用 google chrome 研發工具檢視 grid 網格

### 11. grid-column, grid-row shorthand
        (1)使用 grid-column 縮寫設定 .box 第一個元素的 grid-column-start 為 1 ，並設定 grid-column-end 為 4
        (2)使用 grid-row 縮寫設定 grid-row-start 為 1 ，並設定 grid-row-end 為 3
        (3)設定 .box 的第二個元素 div 2 的顏色為紫色
        (4)設定 grid-column 為 1 / 5
        (5)設定 grid-row 為 3 / 4

### 12. align-content, justify-content, place-content
        (1)設定 .box 第一個元素的 display 為 grid，align-content 為 end
        (2)修改 align-content 為 center
        (3)修改 align-content 為 start
        (4)修改 align-content 為 center，justify-content 為 start
        (5)修改 justify-content 為 end
        (6)修改 justify-content 為 center
        (7)使用 place-content 縮寫設定 align-content 為 end，並設定 justify-content 為 center
        (8)修改 place-content 為 center

### 13. Adding HTML for grid-template-areas
        在 html 添加 Hearder, Sidebar, Footer

### 14. grid-template-areas, grid-area
        (1)在 body 中，設定 display 為 grid
        (2)設定 grid-template-columns 為 repeat(9, 1fr)
        (3)設定 grid-auto-rows 為 75px auto 75px
        (4)設定 grid-template-areas，hd 代表 header，mn 代表 main，sb 代表 sidebar，ft 代表 footer
        (5)在 .el 中，設定背景為 rebeccapurple，文字顏色為白色，display 為 grid，place-content 為 center
        (6)在 .header 中，設定 grid-area 為 hd
        (7)在 .sidebar 中，設定 grid-area 為 sb，背景為藍色
        (8)在 .footer 中，設定 grid-area 為 ft
        (9)在 .container 中，設定 grid-area 為 mn

### 15. Experimenting with layout properties
        開啟 Google Chrome 瀏覽器觀察 Layout
        
        (1)在 body 中，設定 gap 為 1rem
        (2)修改 gap 為 0.5rem
        (3)修改 gap 為 column-gap

### 16. CSS Grid Garden
        https://cssgridgarden.com/
        
        