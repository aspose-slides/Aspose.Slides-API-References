---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: プレゼンテーション全体のビュー プロパティです。
type: docs
url: /ja/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

プレゼンテーション全体のビュー プロパティです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLastView()](#getLastView--) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [setLastView(int value)](#setLastView-int-) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [getShowComments()](#getShowComments--) | スライド コメントを表示するかどうかを指定します。 |
| [setShowComments(byte value)](#setShowComments-byte-) | スライド コメントを表示するかどうかを指定します。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | スライド ビュー モードに関連付けられた共通のビュー プロパティを指定します。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | ノート ビュー モードに関連付けられた共通のビュー プロパティを指定します。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 通常のビュー プロパティを表します。 |
| [getGridSpacing()](#getGridSpacing--) | プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で取得または設定します。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で取得または設定します。 |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。読み取り/書き込み [ViewType](../../com.aspose.slides/viewtype)。

**戻り値:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。読み取り/書き込み [ViewType](../../com.aspose.slides/viewtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

スライド コメントを表示するかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

スライド コメントを表示するかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

スライド ビュー モードに関連付けられた共通のビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ノート ビュー モードに関連付けられた共通のビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

通常のビュー プロパティを表します。通常ビューは 3 つのコンテンツ領域で構成されます：スライド自体、サイド コンテンツ領域、および下部コンテンツ領域。読み取り専用 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**戻り値:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で取得または設定します。読み取り/書き込み float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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
public abstract void setGridSpacing(float value)
```

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で取得または設定します。読み取り/書き込み float。

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |