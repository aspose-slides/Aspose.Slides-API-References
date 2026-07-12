---
title: INotesSlideManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: ノートスライドマネージャー。
type: docs
url: /ja/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

ノートスライドマネージャー。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 現在のスライドのノートスライドを返します。 |
| [addNotesSlide()](#addNotesSlide--) | 現在のスライドのノートスライドを返します。存在しない場合は作成します。 |
| [removeNotesSlide()](#removeNotesSlide--) | 現在のスライドのノートスライドを削除します。 |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

現在のスライドのノートスライドを返します。スライドにノートスライドがない場合は null を返します。読み取り専用 [INotesSlide](../../com.aspose.slides/inotesslide)。

**戻り値:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

現在のスライドのノートスライドを返します。存在しない場合は作成します。

**戻り値:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) このスライド用。
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

現在のスライドのノートスライドを削除します。