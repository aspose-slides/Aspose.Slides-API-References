---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Master notes slide manager.
type: docs
url: /ja/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

マスターノートスライドマネージャー。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | このプレゼンテーションのすべてのノートスライドのマスターが存在する場合はそれを返し、存在しない場合は null を返します。 |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | 関連するノートスライドに対してデフォルトのマスターノートスライドを設定します。 |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | マスターノートスライドを削除します。 |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```


このプレゼンテーションのすべてのノートスライドのマスターが存在する場合はそれを返し、存在しない場合は null を返します。読み取り専用 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)。

**戻り値:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```


関連するノートスライドに対してデフォルトのマスターノートスライドを設定します。

**戻り値:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - デフォルトのマスターノートスライド [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```


マスターノートスライドを削除します。