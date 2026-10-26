---
title: IPortion
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: テキスト段落内のテキストの一部を表します。
type: docs
url: /ja/com.aspose.slides/iportion/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

テキスト段落内のテキストの一部を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 継承が適用されていない、テキストの一部に明示的に設定された書式プロパティを含む書式オブジェクトを返します。 |
| [getText()](#getText--) | 部分のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | 部分のプレーンテキストを取得または設定します。 |
| [getField()](#getField--) | この部分のフィールドを返します。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | この部分を自動更新フィールドに変換します。 |
| [addField(String internalString)](#addField-java.lang.String-) | この部分を自動更新フィールドに変換します。 |
| [removeField()](#removeField--) | このフィールド部分をシンプルな部分に変換します。 |
| [getRect()](#getRect--) | 部分を囲む矩形の座標を取得します。 |
| [getCoordinates()](#getCoordinates--) | 部分の開始位置の座標を取得します。 |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

テキストの一部に明示的に設定された書式プロパティを含む書式オブジェクトを返します。読み取り専用 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

書式オブジェクトは現在の部分のみで定義された書式パラメータを含み、継承されたデータは適用されません。

継承された値を含む実効値を取得するには、[IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) メソッドを使用してください。

**返り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

部分のプレーンテキストを取得または設定します。読み書き可能 String。

**値:** テキスト。

**返り値:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

部分のプレーンテキストを取得または設定します。読み書き可能 String。

**値:** テキスト。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

この部分のフィールドを返します。読み取り専用 [IField](../../com.aspose.slides/ifield)。

**返り値:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

この部分を自動更新フィールドに変換します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | フィールドの型 [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

この部分を自動更新フィールドに変換します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String の内部名 |

### removeField() {#removeField--}
```
public abstract void removeField()
```

このフィールド部分をシンプルな部分に変換します。

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

部分を囲む矩形の座標を取得します。矩形は部分内のすべてのテキスト行（空行を含む）を含みます。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**返り値:**
android.graphics.RectF - 部分を囲む矩形 android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

部分の開始位置の座標を取得します。X 座標は左側ベアリングを含む最初の文字からの開始位置を表し、Y 座標は上側ベアリングを含みます。

**返り値:**
android.graphics.PointF - 部分の開始位置の座標 android.graphics.PointF