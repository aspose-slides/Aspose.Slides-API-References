---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Java API Reference
description: 主講義投影片管理器。
type: docs
url: /zh-hant/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

主講義投影片管理器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | 如果存在，傳回此簡報的所有備註投影片的主投影片，否則傳回 null。 |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | 將預設的主講義投影片設定為相關的講義投影片。 |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | 移除主講義投影片。 |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

傳回此簡報的所有備註投影片的主投影片（如果有），否則傳回 null。 唯讀 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

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