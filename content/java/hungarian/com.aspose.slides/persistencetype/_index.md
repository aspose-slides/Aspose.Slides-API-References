---
title: PersistenceType
second_title: Aspose.Slides for Java API referenciája
description: Megadja a módszert, amelyet az ActiveX vezérlő tulajdonságainak tárolásához használnak.
type: docs
url: /hu/com.aspose.slides/persistencetype/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Megadja a módszert, amelyet az ActiveX control tulajdonságainak tárolásához használnak.
## Mezők

| Mező | Leírás |
| --- | --- |
| [NotDefined](#NotDefined) | A persistance azonosító nincs megadva. |
| [PersistPropertyBag](#PersistPropertyBag) | Megadja, hogy az ActiveX control property-bag-alapú tartósságot használ. |
| [PersistStream](#PersistStream) | Megadja, hogy az ActiveX control stream-alapú tartósságot használ, amely nem támogatja az ActiveX control alapértelmezett állapotba történő inicializálását. |
| [PersistStreamInit](#PersistStreamInit) | Megadja, hogy az ActiveX control stream-alapú tartósságot használ, amely támogatja az ActiveX control alapértelmezett állapotba történő inicializálását. |
| [PersistStorage](#PersistStorage) | Megadja, hogy az ActiveX control storage-alapú tartósságot használ. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

A persistance azonosító nincs megadva.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Megadja, hogy az ActiveX control property-bag-alapú tartósságot használ. A property-bag-alapú tartósság az ActiveX controlt név-érték párok gyűjteménye segítségével tárolja, amelyek meghatározzák a vezérlő által tárolt adatokat.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Megadja, hogy az ActiveX control stream-alapú tartósságot használ, amely nem támogatja az ActiveX control alapértelmezett állapotba történő inicializálását.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Megadja, hogy az ActiveX control stream-alapú tartósságot használ, amely támogatja az ActiveX control alapértelmezett állapotba történő inicializálását.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Megadja, hogy az ActiveX control storage-alapú tartósságot használ.