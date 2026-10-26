---
title: Storage
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示用于 的临时数据存储。
type: docs
url: /zh/com.aspose.slides/storage/
---
**继承：**
java.lang.Object
```
public final class Storage
```

表示 [WebDocument](../../com.aspose.slides/webdocument) 的临时数据存储。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Storage()](#Storage--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | 将值放入存储。 |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | 从存储中获取数据。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定存储是否包含具有指定键的元素。 |

### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

将值放入存储。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的键。 |
| value | TValue | 值。 |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

从存储中获取数据。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的键。 |

**返回值：**
TValue - 如果在数据集合中存在则返回数据值，否则返回 null。

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

确定存储是否包含具有指定键的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 值的键。 |

**返回值：**
boolean - 如果存储包含具有指定键的元素则返回 True，否则返回 false。