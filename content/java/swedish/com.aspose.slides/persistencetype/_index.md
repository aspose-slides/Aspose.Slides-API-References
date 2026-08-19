---
title: PersistenceType
second_title: Aspose.Slides för Java API-referens
description: Anger den metod som används för att lagra egenskaperna för ActiveX-kontrollen.
type: docs
url: /sv/com.aspose.slides/persistencetype/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Anger den metod som används för att lagra egenskaperna för ActiveX-kontrollen.
## Fält

| Field | Description |
| --- | --- |
| [NotDefined](#NotDefined) | Persistens-id har inte angetts. |
| [PersistPropertyBag](#PersistPropertyBag) | Anger att ActiveX-kontrollen lagras med property-bag-baserad persistens. |
| [PersistStream](#PersistStream) | Anger att ActiveX-kontrollen lagras med stream-baserad persistens som inte stödjer initiering av ActiveX-kontrollen till ett standardtillstånd. |
| [PersistStreamInit](#PersistStreamInit) | Anger att ActiveX-kontrollen lagras med stream-baserad persistens som stödjer initiering av ActiveX-kontrollen till ett standardtillstånd. |
| [PersistStorage](#PersistStorage) | Anger att ActiveX-kontrollen lagras med storage-baserad persistens. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Persistens-id har inte angetts.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Anger att ActiveX-kontrollen lagras med property-bag-baserad persistens. Property-bag-baserad persistens lagrar en ActiveX-kontroll med hjälp av en samling av namn- och värdepar som specificerar de data som persisteras av ActiveX-kontrollen.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Anger att ActiveX-kontrollen lagras med stream-baserad persistens som inte stödjer initiering av ActiveX-kontrollen till ett standardtillstånd.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Anger att ActiveX-kontrollen lagras med stream-baserad persistens som stödjer initiering av ActiveX-kontrollen till ett standardtillstånd.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Anger att ActiveX-kontrollen lagras med storage-baserad persistens.