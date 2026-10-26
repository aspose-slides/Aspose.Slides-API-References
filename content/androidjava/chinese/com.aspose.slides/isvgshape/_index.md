---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 SVG 形状的选项。
type: docs
url: /zh/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

表示 SVG 形状的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | 为形状设置事件处理程序 |
| [getId()](#getId--) | 设置或获取形状的 id |
| [setId(String value)](#setId-java.lang.String-) | 设置或获取形状的 id |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

为形状设置事件处理程序

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | int | 事件的类型。 |
| handler | java.lang.String | 处理事件的 Javascript 函数。Null 值会删除处理程序。 |

### getId() {#getId--}
```
public abstract String getId()
```

设置或获取形状的 id

**返回值:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

设置或获取形状的 id

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |