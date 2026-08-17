---
title: IWarningInfo
second_title: Aspose.Slides Java API 参考
description: 表示所有警告的基础接口。
type: docs
url: /zh/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

表示所有警告的基础接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | 如果 receiver 为 null，则结束向指定接收器的警告，并在接收器决定中止操作时抛出 AbortRequestedException。 |
| [getWarningType()](#getWarningType--) | 返回警告的类型。 |
| [getDescription()](#getDescription--) | 返回此警告的可读描述。 |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


如果 receiver 为 null，则结束向指定接收器的警告，并在接收器决定中止操作时抛出 AbortRequestedException。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | 接收器对象 [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


返回警告的类型。只读 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType)。

**返回:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


返回此警告的可读描述。只读 String。

**返回:**
java.lang.String