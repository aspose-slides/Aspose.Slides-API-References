---
title: IWarningInfo
second_title: Aspose.Slides for Java API 參考文件
description: 代表所有警告的基礎介面。
type: docs
url: /zh-hant/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

代表所有警告的基礎介面。
## 方法

| 方法 | 說明 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | 如果 receiver 不為 null，則將警告傳送給指定的 receiver，並在 receiver 決定中止操作時拋出 AbortRequestedException。 |
| [getWarningType()](#getWarningType--) | 傳回警告的類型。 |
| [getDescription()](#getDescription--) | 傳回此警告的可讀說明。 |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


如果 receiver 不為 null，則將警告傳送給指定的 receiver，並在 receiver 決定中止操作時拋出 AbortRequestedException。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | 接收器物件 [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


傳回警告的類型。唯讀 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)。

**傳回：**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


傳回此警告的可讀說明。唯讀 String。

**傳回：**
java.lang.String