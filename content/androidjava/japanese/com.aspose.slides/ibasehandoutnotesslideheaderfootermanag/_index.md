---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレースホルダーの動作を保持するマネージャーです。ヘッダー プレースホルダーは、すべてのタイプの配布資料およびノート スライドに含まれます。
type: docs
url: /ja/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

プレースホルダーの動作を保持するマネージャーを表します。ヘッダー プレースホルダーは、すべての種類の配布資料およびノート スライドに含まれます。

--------------------

元のインターフェイス名 "IBaseHandoutNotesSlideHeaderFooterManager" は、COM 互換性のために "IBaseHandoutNotesSlideHeaderFooterManag" に切り詰められました (型名の長さは 39 文字以下である必要があります)。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | ヘッダー プレースホルダーが存在することを示す値を取得します。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | スライド ヘッダー プレースホルダーの表示状態を変更します。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | スライド ヘッダー プレースホルダーにテキストを設定します。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


ヘッダー プレースホルダーが存在することを示す値を取得します。ブール値を取得します。

**戻り値:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


スライド ヘッダー プレースホルダーの表示状態を変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示にし、そうでない場合は非表示にします。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


スライド ヘッダー プレースホルダーにテキストを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |