---
title: SmartArtNode
second_title: Aspose.Slides for Android の Java API リファレンス
description: SmartArt オブジェクトのノードを表します
type: docs
url: /ja/com.aspose.slides/smartartnode/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)  
```
public final class SmartArtNode implements ISmartArtNode
```

SmartArt オブジェクトのノードを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 現在のノードのすべての子ノードのコレクションを返します。 |
| [getShapes()](#getShapes--) | ノードに関連付けられたすべてのシェイプのコレクションを返します。 |
| [getTextFrame()](#getTextFrame--) | ノードのテキスト フレームを返します。 |
| [isAssistant()](#isAssistant--) | ノードをアシスタントとして取得または設定します。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | ノードをアシスタントとして取得または設定します。 |
| [getLevel()](#getLevel--) | ノードのネスティング レベルを返します。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 |
| [getPosition()](#getPosition--) | 兄弟ノード間でのノードのゼロベース位置を取得または設定します。 |
| [setPosition(int value)](#setPosition-int-) | 兄弟ノード間でのノードのゼロベース位置を取得または設定します。 |
| [isHidden()](#isHidden--) | このノードがデータ モデル内の非表示ノードであるかどうかを返します。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 現在のノードに関連付けられた組織図レイアウト タイプを取得または設定します。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 現在のノードに関連付けられた組織図レイアウト タイプを取得または設定します。 |
| [remove()](#remove--) | 現在のノードを削除します。 |

### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

現在のノードのすべての子ノードのコレクションを返します。読み取り専用 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**戻り値:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

ノードに関連付けられたすべてのシェイプのコレクションを返します。読み取り専用 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**戻り値:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

ノードのテキスト フレームを返します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

ノードをアシスタントとして取得または設定します。読み書き boolean。

**戻り値:**  
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

ノードをアシスタントとして取得または設定します。読み書き boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```

ノードのネスティング レベルを返します。読み取り専用 int。

**戻り値:**  
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 特定の SmartArt レイアウトタイプではノードに箇条書きが提供されないため、null を返す場合があります。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

兄弟ノード間でのノードのゼロベース位置を取得または設定します。読み書き int 。

**戻り値:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

兄弟ノード間でのノードのゼロベース位置を取得または設定します。読み書き int 。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

このノードがデータ モデル内の非表示ノードであるかどうかを返します。読み取り専用 boolean。

**戻り値:**  
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

現在のノードに関連付けられた組織図レイアウト タイプを取得または設定します。読み書き [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**戻り値:**  
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

現在のノードに関連付けられた組織図レイアウト タイプを取得または設定します。読み書き [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```

現在のノードを削除します。

**戻り値:**  
boolean - 成功した場合は true、そうでない場合は false