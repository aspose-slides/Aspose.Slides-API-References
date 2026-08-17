---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides for Java API リファレンス
description: プレースホルダーの動作を保持するマネージャーを表します。すべての種類の配布資料およびノート スライドのヘッダー プレースホルダーを含みます。
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

元のインターフェイス名 "IBaseHandoutNotesSlideHeaderFooterManager" は COM 互換性のために "IBaseHandoutNotesSlideHeaderFooterManag" に短縮されています (型名の長さは 39 文字以下である必要があります)。
## メソッド

| Method | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | ヘッダー プレースホルダーが存在するかどうかを示す値を取得します。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | スライドのヘッダー プレースホルダーの表示状態を変更します。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | スライドのヘッダー プレースホルダーにテキストを設定します。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

ヘッダー プレースホルダーが存在するかどうかを示す値を取得します。 boolean を読み取ります。

**戻り値:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

スライドのヘッダー プレースホルダーの表示状態を変更します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false - ヘッダー プレースホルダーを非表示にします。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

スライドのヘッダー プレースホルダーにテキストを設定します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |