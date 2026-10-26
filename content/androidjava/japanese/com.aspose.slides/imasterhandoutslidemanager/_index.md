---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: マスターハンドアウトスライドマネージャー。
type: docs
url: /ja/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

マスターハンドアウトスライドマネージャー。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | このプレゼンテーションのすべてのノートスライドに対するマスターを返します（存在する場合）。存在しない場合は null を返します。 |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | 関連するハンドアウトスライドにデフォルトのマスターハンドアウトスライドを設定します。 |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | マスターハンドアウトスライドを削除します。 |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

このプレゼンテーションのすべてのノートスライドに対するマスターを返します（存在する場合）。存在しない場合は null を返します。 読み取り専用 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)。

**戻り値:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

関連するハンドアウトスライドにデフォルトのマスターハンドアウトスライドを設定します。

**戻り値:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - マスターハンドアウトスライド [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

マスターハンドアウトスライドを削除します。