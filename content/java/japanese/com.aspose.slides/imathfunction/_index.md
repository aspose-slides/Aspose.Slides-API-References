---
title: IMathFunction
second_title: Aspose.Slides for Java API リファレンス
description: 引数の関数を指定します。
type: docs
url: /ja/com.aspose.slides/imathfunction/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

引数の関数を指定します。

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | 関数名 例として、関数名は sin と cos です |
| [getBase()](#getBase--) | 関数の引数 |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

関数名 例として、関数名は sin と cos です

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

関数の引数

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)