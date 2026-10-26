---
title: ViewProperties
second_title: Aspose.Slides の Java 用 API リファレンス
description: プレゼンテーション全体のビュー プロパティ。
type: docs
url: /ja/com.aspose.slides/viewproperties/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

プレゼンテーション全体のビュー プロパティ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLastView()](#getLastView--) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [setLastView(int value)](#setLastView-int-) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [getShowComments()](#getShowComments--) | スライド コメントを表示するかどうかを指定します。 |
| [setShowComments(byte value)](#setShowComments-byte-) | スライド コメントを表示するかどうかを指定します。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 通常ビューのプロパティを表します。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | スライド ビュー モードに関連付けられた共通ビュー プロパティを指定します。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | ノート ビュー モードに関連付けられた共通ビュー プロパティを指定します。 |
| [getGridSpacing()](#getGridSpacing--) | プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔（ポイント単位）を取得または設定します。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔（ポイント単位）を取得または設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。読み取り/書き込み [ViewType](../../com.aspose.slides/viewtype)。

**戻り値:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。読み取り/書き込み [ViewType](../../com.aspose.slides/viewtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

スライド コメントを表示するかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

スライド コメントを表示するかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

通常ビューのプロパティを表します。通常ビューは 3 つのコンテンツ領域で構成されます：スライド自体、側面コンテンツ領域、底部コンテンツ領域。読み取り専用 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**戻り値:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

スライド ビュー モードに関連付けられた共通ビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

ノート ビュー モードに関連付けられた共通ビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

> ```
> 以下のサンプルコードは、PowerPoint プレゼンテーションでグリッド間隔を変更する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

グリッド間隔の値は正の数でなければなりません。典型的な値の範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

**戻り値:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

> ```
> 以下のサンプルコードは、PowerPoint プレゼンテーションでグリッド間隔を変更する方法を示しています。
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

グリッド間隔の値は正の数でなければなりません。典型的な値の範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject