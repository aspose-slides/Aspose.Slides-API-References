---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: プレゼンテーション全体のビュー プロパティ。
type: docs
url: /ja/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

プレゼンテーション全体のビュー プロパティ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLastView()](#getLastView--) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [setLastView(int value)](#setLastView-int-) | プレゼンテーション ドキュメントが最後に保存されたときに使用されたビュー モードを指定します。 |
| [getShowComments()](#getShowComments--) | スライドコメントが表示されるかどうかを指定します。 |
| [setShowComments(byte value)](#setShowComments-byte-) | スライドコメントが表示されるかどうかを指定します。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | スライドビュー モードに関連付けられた共通ビュー プロパティを指定します。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | ノート ビュー モードに関連付けられた共通ビュー プロパティを指定します。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 通常ビュー プロパティを表します。 |
| [getGridSpacing()](#getGridSpacing--) | プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント）を取得または設定します。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント）を取得または設定します。 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

スライドコメントが表示されるかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

スライドコメントが表示されるかどうかを指定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

スライドビュー モードに関連付けられた共通ビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ノート ビュー モードに関連付けられた共通ビュー プロパティを指定します。読み取り専用 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**戻り値:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

通常ビュー プロパティを表します。通常ビューは、スライド自体、サイド コンテンツ領域、および下部コンテンツ領域の 3 つのコンテンツ領域で構成されます。読み取り専用 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**戻り値:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント）を取得または設定します。読み取り/書き込み float.

--------------------

> ```
> 以下のサンプルコードは、PowerPoint プレゼンテーションのグリッド間隔を変更する方法を示しています。
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

グリッド間隔の値は正の数である必要があります。典型的な範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

**戻り値:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント）を取得または設定します。読み取り/書き込み float.

--------------------

> ```
> 以下のサンプルコードは、PowerPoint プレゼンテーションのグリッド間隔を変更する方法を示しています。
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

グリッド間隔の値は正の数である必要があります。典型的な範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |