---
title: ISection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片的區段。
type: docs
url: /zh-hant/com.aspose.slides/isection/
---```
public interface ISection
```

表示投影片的區段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 區段的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 區段的名稱。 |
| [getSectionId()](#getSectionId--) | 區段 Id。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 傳回區段的第一張投影片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 傳回區段中投影片的清單。 |
### getName() {#getName--}
```
public abstract String getName()
```


區段的名稱。

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


區段的名稱。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


區段 Id。

**傳回：**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


傳回區段的第一張投影片。

**傳回：**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


傳回區段中投影片的清單。

**傳回：**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 投影片清單 [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)