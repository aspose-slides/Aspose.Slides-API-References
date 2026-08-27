---
title: NumberedBulletStyle
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/numberedbulletstyle/
---
## NumberedBulletStyle 类

 表示编号项目符号的样式。
 

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[NotDefined](#NotDefined) | -1 | 未定义。 |
[BulletAlphaLCPeriod](#BulletAlphaLCPeriod) | 0 | 小写字母加句点。示例：a., b., c., ... |
[BulletAlphaUCPeriod](#BulletAlphaUCPeriod) | 1 | 大写字母加句点。示例：A., B., C., ... |
[BulletArabicParenRight](#BulletArabicParenRight) | 2 | 阿拉伯数字加右括号。示例：1), 2), 3), ... |
[BulletArabicPeriod](#BulletArabicPeriod) | 3 | 阿拉伯数字加句点。示例：1., 2., 3., ... |
[BulletRomanLCParenBoth](#BulletRomanLCParenBoth) | 4 | 小写罗马数字加双括号。示例：(i), (ii), (iii), ... |
[BulletRomanLCParenRight](#BulletRomanLCParenRight) | 5 | 小写罗马数字加右括号。示例：i), ii), iii), ... |
[BulletRomanLCPeriod](#BulletRomanLCPeriod) | 6 | 小写罗马数字加句点。示例：i., ii., iii., ... |
[BulletRomanUCPeriod](#BulletRomanUCPeriod) | 7 | 大写罗马数字加句点。示例：I., II., III., ... |
[BulletAlphaLCParenBoth](#BulletAlphaLCParenBoth) | 8 | 小写字母加双括号。示例：(a), (b), (c), ... |
[BulletAlphaLCParenRight](#BulletAlphaLCParenRight) | 9 | 小写字母加右括号。示例：a), b), c), ... |
[BulletAlphaUCParenBoth](#BulletAlphaUCParenBoth) | 10 | 大写字母加双括号。示例：(A), (B), (C), ... |
[BulletAlphaUCParenRight](#BulletAlphaUCParenRight) | 11 | 大写字母加右括号。示例：A), B), C), ... |
[BulletArabicParenBoth](#BulletArabicParenBoth) | 12 | 阿拉伯数字加双括号。示例：(1), (2), (3), ... |
[BulletArabicPlain](#BulletArabicPlain) | 13 | 阿拉伯数字。示例：1, 2, 3, ... |
[BulletRomanUCParenBoth](#BulletRomanUCParenBoth) | 14 | 大写罗马数字加双括号。示例：(I), (II), (III), ... |
[BulletRomanUCParenRight](#BulletRomanUCParenRight) | 15 | 大写罗马数字加右括号。示例：I), II), III), ... |
[BulletSimpChinPlain](#BulletSimpChinPlain) | 16 | 简体中文（无句点）。 |
[BulletSimpChinPeriod](#BulletSimpChinPeriod) | 17 | 简体中文（带句点）。 |
[BulletCircleNumDBPlain](#BulletCircleNumDBPlain) | 18 | 双字节圈号，适用于 1 到 10，11 以后使用阿拉伯数字。 |
[BulletCircleNumWDWhitePlain](#BulletCircleNumWDWhitePlain) | 19 | 文本颜色数字，周围绘制相同颜色的圆环（Wingdings 白色圆圈数字）。11 以后使用阿拉伯数字。 |
[BulletCircleNumWDBlackPlain](#BulletCircleNumWDBlackPlain) | 20 | 阴影颜色数字，圆形背景为普通文本颜色（Wingdings 黑色圆圈数字）。 |
[BulletTradChinPlain](#BulletTradChinPlain) | 21 | 繁体中文（无句点）。 |
[BulletTradChinPeriod](#BulletTradChinPeriod) | 22 | 繁体中文（带句点）。 |
[BulletArabicAlphaDash](#BulletArabicAlphaDash) | 23 | 阿拉伯语字母加破折号。 |
[BulletArabicAbjadDash](#BulletArabicAbjadDash) | 24 | 阿拉伯字母表（Abjad）加破折号。 |
[BulletHebrewAlphaDash](#BulletHebrewAlphaDash) | 25 | 希伯来语字母加破折号。 |
[BulletKanjiKoreanPlain](#BulletKanjiKoreanPlain) | 26 | 日语/韩语数字（无句点）。 |
[BulletKanjiKoreanPeriod](#BulletKanjiKoreanPeriod) | 27 | 日语/韩语数字（带句点）。 |
[BulletArabicDBPlain](#BulletArabicDBPlain) | 28 | 双字节阿拉伯数字编号方案（无标点）。 |
[BulletArabicDBPeriod](#BulletArabicDBPeriod) | 29 | 双字节阿拉伯数字编号方案，使用双字节句点。 |
[BulletThaiAlphaPeriod](#BulletThaiAlphaPeriod) | 30 | 泰文字母句点。 |
[BulletThaiAlphaParenRight](#BulletThaiAlphaParenRight) | 31 | 泰文字母右括号。 |
[BulletThaiAlphaParenBoth](#BulletThaiAlphaParenBoth) | 32 | 泰文字母双括号。 |
[BulletThaiNumPeriod](#BulletThaiNumPeriod) | 33 | 泰文数字句点。 |
[BulletThaiNumParenRight](#BulletThaiNumParenRight) | 34 | 泰文数字右括号。 |
[BulletThaiNumParenBoth](#BulletThaiNumParenBoth) | 35 | 泰文数字双括号。 |
[BulletHindiAlphaPeriod](#BulletHindiAlphaPeriod) | 36 | 印地文字母句点（元音）。 |
[BulletHindiNumPeriod](#BulletHindiNumPeriod) | 37 | 印地数字句点。 |
[BulletKanjiSimpChinDBPeriod](#BulletKanjiSimpChinDBPeriod) | 38 | 汉字简体中文双字节句点。 |
[BulletHindiNumParenRight](#BulletHindiNumParenRight) | 39 | 印地数字右括号。 |
[BulletHindiAlpha1Period](#BulletHindiAlpha1Period) | 40 | 印地文字母句点（辅音）。 |


---


### NotDefined {#NotDefined}
未定义。

---

### BulletAlphaLCPeriod {#BulletAlphaLCPeriod}
小写字母加句点。示例：a., b., c., ...

---

### BulletAlphaUCPeriod {#BulletAlphaUCPeriod}
大写字母加句点。示例：A., B., C., ...

---

### BulletArabicParenRight {#BulletArabicParenRight}
阿拉伯数字加右括号。示例：1), 2), 3), ...

---

### BulletArabicPeriod {#BulletArabicPeriod}
阿拉伯数字加句点。示例：1., 2., 3., ...

---

### BulletRomanLCParenBoth {#BulletRomanLCParenBoth}
小写罗马数字加双括号。示例：(i), (ii), (iii), ...

---

### BulletRomanLCParenRight {#BulletRomanLCParenRight}
小写罗马数字加右括号。示例：i), ii), iii), ...

---

### BulletRomanLCPeriod {#BulletRomanLCPeriod}
小写罗马数字加句点。示例：i., ii., iii., ...

---

### BulletRomanUCPeriod {#BulletRomanUCPeriod}
大写罗马数字加句点。示例：I., II., III., ...

---

### BulletAlphaLCParenBoth {#BulletAlphaLCParenBoth}
小写字母加双括号。示例：(a), (b), (c), ...

---

### BulletAlphaLCParenRight {#BulletAlphaLCParenRight}
小写字母加右括号。示例：a), b), c), ...

---

### BulletAlphaUCParenBoth {#BulletAlphaUCParenBoth}
大写字母加双括号。示例：(A), (B), (C), ...

---

### BulletAlphaUCParenRight {#BulletAlphaUCParenRight}
大写字母加右括号。示例：A), B), C), ...

---

### BulletArabicParenBoth {#BulletArabicParenBoth}
阿拉伯数字加双括号。示例：(1), (2), (3), ...

---

### BulletArabicPlain {#BulletArabicPlain}
阿拉伯数字。示例：1, 2, 3, ...

---

### BulletRomanUCParenBoth {#BulletRomanUCParenBoth}
大写罗马数字加双括号。示例：(I), (II), (III), ...

---

### BulletRomanUCParenRight {#BulletRomanUCParenRight}
大写罗马数字加右括号。示例：I), II), III), ...

---

### BulletSimpChinPlain {#BulletSimpChinPlain}
简体中文（无句点）。

---

### BulletSimpChinPeriod {#BulletSimpChinPeriod}
简体中文（带句点）。

---

### BulletCircleNumDBPlain {#BulletCircleNumDBPlain}
双字节圈号，适用于 1 到 10，11 以后使用阿拉伯数字。

---

### BulletCircleNumWDWhitePlain {#BulletCircleNumWDWhitePlain}
文本颜色数字，周围绘制相同颜色的圆环（Wingdings 白色圆圈数字）。11 以后使用阿拉伯数字。

---

### BulletCircleNumWDBlackPlain {#BulletCircleNumWDBlackPlain}
阴影颜色数字，圆形背景为普通文本颜色（Wingdings 黑色圆圈数字）。

---

### BulletTradChinPlain {#BulletTradChinPlain}
繁体中文（无句点）。

---

### BulletTradChinPeriod {#BulletTradChinPeriod}
繁体中文（带句点）。

---

### BulletArabicAlphaDash {#BulletArabicAlphaDash}
阿拉伯语字母加破折号。

---

### BulletArabicAbjadDash {#BulletArabicAbjadDash}
阿拉伯字母表（Abjad）加破折号。

---

### BulletHebrewAlphaDash {#BulletHebrewAlphaDash}
希伯来语字母加破折号。

---

### BulletKanjiKoreanPlain {#BulletKanjiKoreanPlain}
日语/韩语数字（无句点）。

---

### BulletKanjiKoreanPeriod {#BulletKanjiKoreanPeriod}
日语/韩语数字（带句点）。

---

### BulletArabicDBPlain {#BulletArabicDBPlain}
双字节阿拉伯数字编号方案（无标点）。

---

### BulletArabicDBPeriod {#BulletArabicDBPeriod}
双字节阿拉伯数字编号方案，使用双字节句点。

---

### BulletThaiAlphaPeriod {#BulletThaiAlphaPeriod}
泰文字母句点。

---

### BulletThaiAlphaParenRight {#BulletThaiAlphaParenRight}
泰文字母右括号。

---

### BulletThaiAlphaParenBoth {#BulletThaiAlphaParenBoth}
泰文字母双括号。

---

### BulletThaiNumPeriod {#BulletThaiNumPeriod}
泰文数字句点。

---

### BulletThaiNumParenRight {#BulletThaiNumParenRight}
泰文数字右括号。

---

### BulletThaiNumParenBoth {#BulletThaiNumParenBoth}
泰文数字双括号。

---

### BulletHindiAlphaPeriod {#BulletHindiAlphaPeriod}
印地文字母句点（元音）。

---

### BulletHindiNumPeriod {#BulletHindiNumPeriod}
印地数字句点。

---

### BulletKanjiSimpChinDBPeriod {#BulletKanjiSimpChinDBPeriod}
汉字简体中文双字节句点。

---

### BulletHindiNumParenRight {#BulletHindiNumParenRight}
印地数字右括号。

---

### BulletHindiAlpha1Period {#BulletHindiAlpha1Period}
印地文字母句点（辅音）。

---