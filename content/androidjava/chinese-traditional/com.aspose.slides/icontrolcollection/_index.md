---
title: IControlCollection
second_title: Aspose.Slides for Android via Java API 參考
description: ActiveX 控制項的集合。
type: docs
url: /zh-hant/com.aspose.slides/icontrolcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX 控制項的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 從集合中移除 ActiveX 控制項。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除位於指定位置的 ActiveX 控制項。 |
| [clear()](#clear--) | 從集合中移除所有控制項。 |
| [get_Item(int index)](#get-Item-int-) | 返回位於指定位置的控制項。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 建立並將新控制項加入集合。 |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

從集合中移除 ActiveX 控制項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 要移除的控制項。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除位於指定位置的 ActiveX 控制項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的控制項索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有控制項。

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

返回位於指定位置的控制項。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 控制項的索引。 |

**返回值:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

建立並將新控制項加入集合。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| controlType | int | 要新增的控制項類型。 |
| x | float | 形狀框架左側的 X 座標。 |
| y | float | 形狀框架上側的 Y 座標。 |
| width | float | 形狀框架的寬度。 |
| height | float | 形狀框架的高度。 |

**返回值:**
[IControl](../../com.aspose.slides/icontrol) - 已建立的控制項 [IControl](../../com.aspose.slides/icontrol)。