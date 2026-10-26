---
title: IMasterTheme
second_title: Aspose.Slides for Java API 參考
description: 表示母版主題。
type: docs
url: /zh-hant/com.aspose.slides/imastertheme/
---
**所有已實作的介面：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

表示母版主題。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 返回附加色彩配置的集合。 |
| [getName()](#getName--) | 返回主題的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 返回主題的名稱。 |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

返回附加色彩配置的集合。这些配置不会影响演示文稿的外观，可选择作为幻灯片的主要色彩配置。只讀 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**傳回值：**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

返回主題的名稱。可讀寫 String。

**傳回值：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回主題的名稱。可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |