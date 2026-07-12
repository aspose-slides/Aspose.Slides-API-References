---
title: IAutoShape
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: AutoShape を表します。
type: docs
url: /ja/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

AutoShape を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape のロックを返します。 |
| [getTextFrame()](#getTextFrame--) | AutoShape の TextFrame オブジェクトを返します。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | このオートシェイプがスタイルまたは塗りつぶし形式ではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判定します。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | このオートシェイプがスタイルまたは塗りつぶし形式ではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判定します。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | シェイプに新しい TextFrame を追加します。 |
| [isTextBox()](#isTextBox--) | シェイプがテキストボックスかどうかを指定します。 |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


AutoShape のロックを返します。 読み取り専用 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**戻り値:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


AutoShape の TextFrame オブジェクトを返します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


このオートシェイプがスタイルまたは塗りつぶし形式ではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判定します。 読み書き可能な boolean。

**戻り値:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


このオートシェイプがスタイルまたは塗りつぶし形式ではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判定します。 読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


シェイプに新しい TextFrame を追加します。シェイプにすでに TextFrame がある場合は、そのテキストを変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrame のデフォルトテキスト。 |

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe) - 新しい [ITextFrame](../../com.aspose.slides/itextframe) オブジェクト。
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


シェイプがテキストボックスかどうかを指定します。

--------------------

シェイプがテキストボックスとして指定されていなくても、テキストを持てないわけではありません。テキストボックスは特定のプロパティを持つ特殊なシェイプにすぎません。

**戻り値:**
boolean