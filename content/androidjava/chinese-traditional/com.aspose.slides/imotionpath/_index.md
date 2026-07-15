---
title: IMotionPath
second_title: Aspose.Slides for Android via Java API 參考
description: 表示運動路徑。
type: docs
url: /zh-hant/com.aspose.slides/imotionpath/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

表示運動路徑。
## 方法

| 方法 | 說明 |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | 將新指令加入路徑 |
| [getCount()](#getCount--) | 傳回集合中路徑的數量。 |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | 將新指令插入路徑 |
| [clear()](#clear--) | 從集合中移除所有指令。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 從集合中移除指定的指令。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的指令。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的指令。 |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令加入路徑

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | android.graphics.PointF[] 的點陣列 |
| ptsType | int | 動畫運動路徑中點的類型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相對座標 boolean |

**傳回值：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 路徑的指令 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

傳回集合中路徑的數量。唯讀 int。

**傳回值：**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令插入路徑

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 指令插入的索引 int |
| type | int | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | android.graphics.PointF[] 的點陣列 |
| ptsType | int | 動畫運動路徑中點的類型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相對座標 boolean |

### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有指令。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

從集合中移除指定的指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要移除的運動路徑 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 移除指令的索引 int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

傳回指定索引處的指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回值：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 指定索引處的指令 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)