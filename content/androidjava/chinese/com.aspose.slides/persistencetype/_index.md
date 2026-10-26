---
title: PersistenceType
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 指定用于存储 ActiveX 控件属性的方法。
type: docs
url: /zh/com.aspose.slides/persistencetype/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

指定用于存储 ActiveX 控件属性的方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [NotDefined](#NotDefined) | 未指定持久性标识。 |
| [PersistPropertyBag](#PersistPropertyBag) | 指定 ActiveX 控件使用基于属性包的持久化进行持久化。 |
| [PersistStream](#PersistStream) | 指定 ActiveX 控件使用基于流的持久化，且不支持将 ActiveX 控件初始化为默认状态。 |
| [PersistStreamInit](#PersistStreamInit) | 指定 ActiveX 控件使用基于流的持久化，且支持将 ActiveX 控件初始化为默认状态。 |
| [PersistStorage](#PersistStorage) | 指定 ActiveX 控件使用基于存储的持久化。 |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

未指定持久性标识。

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

指定 ActiveX 控件使用基于属性包的持久化。基于属性包的持久化通过一组名称和值对来存储 ActiveX 控件，这些对指定了由 ActiveX 控件持久化的数据。

### PersistStream {#PersistStream}
``` 
public static final int PersistStream
```

指定 ActiveX 控件使用基于流的持久化，且不支持将 ActiveX 控件初始化为默认状态。

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

指定 ActiveX 控件使用基于流的持久化，且支持将 ActiveX 控件初始化为默认状态。

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

指定 ActiveX 控件使用基于存储的持久化。