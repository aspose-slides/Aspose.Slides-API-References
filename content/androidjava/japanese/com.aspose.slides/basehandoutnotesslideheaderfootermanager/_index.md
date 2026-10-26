---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレースホルダーの動作を保持するマネージャーを表します。ヘッダー プレースホルダーは、配布資料やノート スライドを含むすべてのタイプに対応しています。
type: docs
url: /ja/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

プレースホルダーの動作を保持するマネージャーを表します。ヘッダー プレースホルダーは、配布資料やノート スライドを含むすべてのタイプに対して利用できます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | ヘッダー プレースホルダーが存在することを示す値を取得します。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | スライド ヘッダー プレースホルダーの表示状態を変更します。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | スライド ヘッダー プレースホルダーにテキストを設定します。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


ヘッダー プレースホルダーが存在することを示す値を取得します。boolean を読み取ります。

**戻り値:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


スライド ヘッダー プレースホルダーの表示状態を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false - 非表示にします。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


スライド ヘッダー プレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |