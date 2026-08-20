---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: 此類別表示用於向長時間執行的任務發出是否已請求中斷信號的代幣。
type: docs
url: /zh-hant/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

此類別表示用於向長時間執行的任務發出是否已請求中斷信號的代幣。

## Methods

| 方法 | 描述 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 如果請求中斷則返回 true。 |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 如果請求中斷則拋出異常。 |

### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

如果請求中斷則返回 true。

**返回：**
boolean

### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

如果請求中斷則拋出異常。