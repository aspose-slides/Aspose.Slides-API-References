---
title: Field
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: フィールドを表します。
type: docs
url: /ja/com.aspose.slides/field/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IField](../../com.aspose.slides/ifield)  
```
public final class Field extends DomObject<Portion> implements IField
```

フィールドを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getType()](#getType--) | フィールドの型を取得または設定します。 |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | フィールドの型を取得または設定します。 |
| [getSlide()](#getSlide--) | 段落の親スライドを取得します。 |
| [getPresentation()](#getPresentation--) | 段落の親プレゼンテーションを取得します。 |
### getType() {#getType--}
```
public final IFieldType getType()
```

フィールドの型を取得または設定します。 読み書き [IFieldType](../../com.aspose.slides/ifieldtype).

**戻り値:**  
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

フィールドの型を取得または設定します。 読み書き [IFieldType](../../com.aspose.slides/ifieldtype).

**パラメータ:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

段落の親スライドを取得します。 読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide).

**戻り値:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

段落の親プレゼンテーションを取得します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation).

**戻り値:**  
[IPresentation](../../com.aspose.slides/ipresentation)