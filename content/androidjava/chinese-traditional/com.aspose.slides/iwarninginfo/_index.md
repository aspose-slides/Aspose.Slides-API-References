---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /zh-hant/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

表示所有警告的基礎介面。

## 方法

| 方法 | 說明 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | 如果 receiver 不為 null，則將警告傳送至指定的 receiver，且若 receiver 決定中止操作，則拋出 AbortRequestedException。 |
| [getWarningType()](#getWarningType--) | 傳回警告的類型。 |
| [getDescription()](#getDescription--) | 傳回此警告的人類可讀說明。 |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


如果 receiver 不為 null，則將警告傳送至指定的 receiver，且若 receiver 決定中止操作，則拋出 AbortRequestedException。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver 物件 [IWarningCallback](../../com.aspose.slides/iwarningcallback) |
### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


傳回警告的類型。唯讀 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)。

**傳回值:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


傳回此警告的人類可讀說明。唯讀 String。

**傳回值:**
java.lang.String