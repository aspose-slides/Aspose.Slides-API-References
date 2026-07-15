---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: 此類別表示用於向長時間執行的任務發送是否已請求中斷的 token。
type: docs
url: /zh-hant/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

此類別表示用於向長時間執行的任務發送是否已請求中斷的 token。

## Methods

| 方法 | 說明 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果已請求中斷，則返回 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果已請求中斷，則拋出例外。 |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

如果已請求中斷，則返回 true。

**返回：**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

如果已請求中斷，則拋出例外。