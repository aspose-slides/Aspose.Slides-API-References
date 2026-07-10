---
title: IControlCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: ActiveX 控件的集合。
type: docs
url: /zh/com.aspose.slides/icontrolcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX 控件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 从集合中移除 ActiveX 控件。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除存储在指定位置的 ActiveX 控件。 |
| [clear()](#clear--) | 从集合中移除所有控件。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定位置的控件。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 创建并向集合中添加一个新控件。 |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

从集合中移除 ActiveX 控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 要移除的控件。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

从集合中移除存储在指定位置的 ActiveX 控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的控件的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有控件。

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

返回指定位置的控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 控件的索引。 |

**返回：**
[IControl](../../com.aspose.slides/icontrol)

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

创建并向集合中添加一个新控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlType | int | 要添加的控件类型。 |
| x | float | 形状框左侧的 X 坐标。 |
| y | float | 形状框顶部的 Y 坐标。 |
| width | float | 形状框的宽度。 |
| height | float | 形状框的高度。 |

**返回：**
[IControl](../../com.aspose.slides/icontrol) - 已创建的控件 [IControl](../../com.aspose.slides/icontrol)。