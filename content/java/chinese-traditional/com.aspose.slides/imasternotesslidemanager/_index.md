---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: 主備註投影片管理器。
type: docs
url: /zh-hant/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

主備註投影片管理器。
## 方法

| Method | Description |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | 若此簡報有主備註投影片則回傳，否則回傳 null。 |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | 為相關備註投影片設定預設主備註投影片。 |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | 移除主備註投影片。 |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```

若此簡報有主備註投影片則回傳，否則回傳 null。唯讀 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)。

**返回：**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```

為相關備註投影片設定預設主備註投影片。

**返回：**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - 預設主備註投影片 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```

移除主備註投影片。