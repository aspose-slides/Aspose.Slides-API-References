---
title: IMasterTheme
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示一個主題範本。
type: docs
url: /zh-hant/com.aspose.slides/imastertheme/
---
**所有已實作的介面：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

表示一個主題範本。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 傳回額外色彩配置的集合。 |
| [getName()](#getName--) | 傳回主題的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回主題的名稱。 |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

傳回額外色彩配置的集合。這些配置不會影響簡報的外觀，使用者可以將其選為投影片的主要色彩配置。唯讀 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**傳回值：**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

傳回主題的名稱。可讀寫 String。

**傳回值：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

傳回主題的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |