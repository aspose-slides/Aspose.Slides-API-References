---
title: PersistenceType
second_title: Aspose.Slides for Java API 參考
description: 指定用於儲存 ActiveX 控制項屬性的方法。
type: docs
url: /zh-hant/com.aspose.slides/persistencetype/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

指定用於儲存 ActiveX 控制項屬性的方法。

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [NotDefined](#NotDefined) | 未指定持久化 ID。 |
| [PersistPropertyBag](#PersistPropertyBag) | 指定 ActiveX 控制項以基於屬性袋的持久化方式保存。 |
| [PersistStream](#PersistStream) | 指定 ActiveX 控制項以基於串流的持久化方式保存，且不支援將 ActiveX 控制項初始化為預設狀態。 |
| [PersistStreamInit](#PersistStreamInit) | 指定 ActiveX 控制項以基於串流的持久化方式保存，且支援將 ActiveX 控制項初始化為預設狀態。 |
| [PersistStorage](#PersistStorage) | 指定 ActiveX 控制項以基於儲存的持久化方式保存。 |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

未指定持久化 ID。

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

指定 ActiveX 控制項以基於屬性袋的持久化方式保存。基於屬性袋的持久化透過名稱和值的集合來儲存 ActiveX 控制項，這些名稱和值指定了由 ActiveX 控制項持久化的資料。

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

指定 ActiveX 控制項以基於串流的持久化方式保存，且不支援將 ActiveX 控制項初始化為預設狀態。

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

指定 ActiveX 控制項以基於串流的持久化方式保存，且支援將 ActiveX 控制項初始化為預設狀態。

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

指定 ActiveX 控制項以基於儲存的持久化方式保存。