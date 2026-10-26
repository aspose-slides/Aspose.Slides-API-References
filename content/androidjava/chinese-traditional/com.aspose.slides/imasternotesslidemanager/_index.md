---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Android via Java API 參考
description: 主備註投影片管理員。
type: docs
url: /zh-hant/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

主備註投影片管理員。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | 如果存在，則返回此簡報所有備註投影片的主投影片；否則返回 null。 |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | 設定相關備註投影片的預設主備註投影片。 |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | 移除主備註投影片。 |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```


如果存在，則返回此簡報所有備註投影片的主投影片；否則返回 null。唯讀 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)。

**返回：**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```


設定相關備註投影片的預設主備註投影片。

**返回：**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - 預設主備註投影片 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```


移除主備註投影片。