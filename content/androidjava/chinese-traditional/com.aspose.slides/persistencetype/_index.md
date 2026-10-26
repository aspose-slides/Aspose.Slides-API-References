---
title: PersistenceType
second_title: Aspose.Slides for Android via Java API 參考
description: 指定用於儲存 ActiveX 控制項屬性的方法。
type: docs
url: /zh-hant/com.aspose.slides/persistencetype/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

指定用於儲存 ActiveX 控制項屬性的方法。

## 欄位

| 欄位 | 描述 |
| --- | --- |
| [NotDefined](#NotDefined) | Persistance id 未指定。 |
| [PersistPropertyBag](#PersistPropertyBag) | 指定 ActiveX 控制項使用基於屬性袋的持久性。 |
| [PersistStream](#PersistStream) | 指定 ActiveX 控制項使用串流為基礎的持久性，且不支援將 ActiveX 控制項初始化為預設狀態。 |
| [PersistStreamInit](#PersistStreamInit) | 指定 ActiveX 控制項使用串流為基礎的持久性，且支援將 ActiveX 控制項初始化為預設狀態。 |
| [PersistStorage](#PersistStorage) | 指定 ActiveX 控制項使用儲存為基礎的持久性。 |

### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Persistance id 未指定。

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

指定 ActiveX 控制項使用基於屬性袋的持久性。基於屬性袋的持久性透過名稱/值配對的集合來儲存 ActiveX 控制項，該集合指定了 ActiveX 控制項所持久化的資料。

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

指定 ActiveX 控制項使用串流為基礎的持久性，且不支援將 ActiveX 控制項初始化為預設狀態。

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

指定 ActiveX 控制項使用串流為基礎的持久性，且支援將 ActiveX 控制項初始化為預設狀態。

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

指定 ActiveX 控制項使用儲存為基礎的持久性。