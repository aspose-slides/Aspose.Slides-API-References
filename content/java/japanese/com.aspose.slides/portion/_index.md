---
title: Portion
second_title: Aspose.Slides for Java API リファレンス
description: テキスト段落内のテキストの一部を表します。
type: docs
url: /ja/com.aspose.slides/portion/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

テキスト段落内のテキストの一部を表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Portion()](#Portion--) | Portion クラスの新しいインスタンスを初期化します。 |
| [Portion(String str)](#Portion-java.lang.String-) | Portion クラスの新しいインスタンスを初期化します。 |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 継承が適用されていない、テキスト部分に明示的に設定された書式設定プロパティを含む書式設定オブジェクトを返します。 |
| [getText()](#getText--) | 部分のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | 部分のプレーンテキストを取得または設定します。 |
| [getField()](#getField--) | この部分のフィールドを返します。 |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | この部分を自動的に更新されるフィールドに変換します。 |
| [addField(String internalString)](#addField-java.lang.String-) | この部分を自動的に更新されるフィールドに変換します。 |
| [removeField()](#removeField--) | このフィールド部分を単純な部分に変換します。 |
| [getRect()](#getRect--) | 部分を囲む矩形の座標を取得します。 |
| [getCoordinates()](#getCoordinates--) | 部分の開始位置の座標を取得します。 |
| [getSlide()](#getSlide--) | テキストの親スライドを返します。 |
| [getPresentation()](#getPresentation--) | テキストの親プレゼンテーションを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


Portion クラスの新しいインスタンスを初期化します。

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


Portion クラスの新しいインスタンスを初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


Portion クラスの新しいインスタンスを初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


継承が適用されていない、テキスト部分に明示的に設定された書式設定プロパティを含む書式設定オブジェクトを返します。 読み取り専用 [IPortionFormat](../../com.aspose.slides/iportionformat)。

--------------------

書式設定オブジェクトには現在の部分だけに定義された書式パラメーターが含まれ、継承されたデータは適用されません。

継承された値を含む有効な値を取得するには [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) メソッドを使用してください。

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


部分のプレーンテキストを取得または設定します。 読み書き String.

値: テキスト。

**戻り値:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


部分のプレーンテキストを取得または設定します。 読み書き String.

値: テキスト。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


この部分のフィールドを返します。 読み取り専用 [IField](../../com.aspose.slides/ifield)。

**戻り値:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


この部分を自動的に更新されるフィールドに変換します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


この部分を自動的に更新されるフィールドに変換します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| internalString | java.lang.String | FieldType の内部名。 |

### removeField() {#removeField--}
```
public final void removeField()
```


このフィールド部分を単純な部分に変換します。

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


部分を囲む矩形の座標を取得します。 この矩形には、空行を含む部分内のすべてのテキスト行が含まれます。

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```


部分の開始位置の座標を取得します。 ポイントの X座標は、左側ベアリングを含む最初の文字からの部分の開始を表します。 Y座標は上側ベアリングを含みます。

**戻り値:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


テキストの親スライドを返します。 読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


テキストの親プレゼンテーションを返します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject