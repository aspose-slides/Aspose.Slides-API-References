---
title: ISmartArtNode
second_title: Aspose.Slides for Android の Java API リファレンス
description: SmartArt ダイアグラムのノードを表します。
type: docs
url: /ja/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

SmartArt ダイアグラムのノードを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 現在のノードのすべての子ノードのコレクションを返します。 |
| [getShapes()](#getShapes--) | ノードに関連付けられたすべてのシェイプのコレクションを返します。 |
| [getTextFrame()](#getTextFrame--) | ノードのテキストを取得または設定します。 |
| [isAssistant()](#isAssistant--) | ノードをアシスタントとして取得または設定します。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | ノードをアシスタントとして取得または設定します。 |
| [getLevel()](#getLevel--) | ノードのネストレベルを返します。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 |
| [getPosition()](#getPosition--) | 兄弟ノード間でのノードのゼロベース位置を取得または設定します。 |
| [setPosition(int value)](#setPosition-int-) | 兄弟ノード間でのノードのゼロベース位置を取得または設定します。 |
| [isHidden()](#isHidden--) | このノードがデータモデル内で非表示ノードである場合は true を返します。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 現在のノードに関連付けられた組織図レイアウトタイプを取得または設定します。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 現在のノードに関連付けられた組織図レイアウトタイプを取得または設定します。 |
| [remove()](#remove--) | 現在のノードを削除します。 |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

現在のノードのすべての子ノードのコレクションを返します。 読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

ノードに関連付けられたすべてのシェイプのコレクションを返します。 読み取り専用 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**戻り値:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

ノードのテキストを取得または設定します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

ノードをアシスタントとして取得または設定します。 読み書き boolean。

**戻り値:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

ノードをアシスタントとして取得または設定します。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

ノードのネストレベルを返します。 読み取り専用 int。

**戻り値:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 注: 特定の SmartArt レイアウトではノードに箇条書きが提供されないため null を返す可能性があります。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

兄弟ノード間でのノードのゼロベース位置を取得または設定します。 読み書き int。

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

兄弟ノード間でのノードのゼロベース位置を取得または設定します。 読み書き int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

このノードがデータモデル内で非表示ノードである場合は true を返します。 読み取り専用 boolean。

**戻り値:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

現在のノードに関連付けられた組織図レイアウトタイプを取得または設定します。 読み書き [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**戻り値:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

現在のノードに関連付けられた組織図レイアウトタイプを取得または設定します。 読み書き [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

現在のノードを削除します。

**戻り値:**
boolean - 削除が成功した場合は true、そうでない場合は false。