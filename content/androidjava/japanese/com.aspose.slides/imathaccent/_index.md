---
title: IMathAccent
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: ベースと結合用ダイアクリティカルマークからなるアクセント機能を指定します 例: ud835udc4eu0301
type: docs
url: /ja/com.aspose.slides/imathaccent/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

ベースと結合用ダイアクリティカルマークからなるアクセント機能を指定します 例: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | アクセントが適用された引数 |
| [getCharacter()](#getCharacter--) | アクセント文字。この値は (U+0300–U+036F) または (U+20D0–U+20EF) の範囲内である必要があります。デフォルト値: 結合サーカムフレックスアクセント (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | アクセント文字。この値は (U+0300–U+036F) または (U+20D0–U+20EF) の範囲内である必要があります。デフォルト値: 結合サーカムフレックスアクセント (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


アクセントが適用された引数

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**戻り値:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


アクセント文字。この値は (U+0300–U+036F) または (U+20D0–U+20EF) の範囲内である必要があります。デフォルト値: 結合サーカムフレックスアクセント (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**戻り値:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


アクセント文字。この値は (U+0300–U+036F) または (U+20D0–U+20EF) の範囲内である必要があります。デフォルト値: 結合サーカムフレックスアクセント (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |