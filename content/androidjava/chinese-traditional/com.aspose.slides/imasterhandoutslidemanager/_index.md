---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: 主講義投影片管理員。
type: docs
url: /zh-hant/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

主講義投影片管理員。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | 如果此簡報有對應的母片，則返回所有註解投影片的母片，否則返回 null。 |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | 將預設的主講義投影片設定為相關的講義投影片。 |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | 移除主講義投影片。 |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```


如果此簡報有對應的母片，則返回所有註解投影片的母片，否則返回 null。唯讀 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)。

**返回:**  
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```


將預設的主講義投影片設定為相關的講義投影片。

**返回:**  
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - 主講義投影片 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```


移除主講義投影片。