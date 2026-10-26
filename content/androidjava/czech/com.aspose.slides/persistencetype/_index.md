---
title: PersistenceType
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Určuje metodu používanou k ukládání vlastností ActiveX ovládacího prvku.
type: docs
url: /cs/com.aspose.slides/persistencetype/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Určuje metodu používanou k ukládání vlastností ActiveX ovládacího prvku.
## Pole

| Pole | Popis |
| --- | --- |
| [NotDefined](#NotDefined) | Identifikátor perzistence není zadán. |
| [PersistPropertyBag](#PersistPropertyBag) | Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na property-bag. |
| [PersistStream](#PersistStream) | Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na proudu, která nepodporuje inicializaci ActiveX ovládacího prvku do výchozího stavu. |
| [PersistStreamInit](#PersistStreamInit) | Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na proudu, která podporuje inicializaci ActiveX ovládacího prvku do výchozího stavu. |
| [PersistStorage](#PersistStorage) | Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na úložišti. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Identifikátor perzistence není zadán.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na property-bag. Perzistence založená na property-bag ukládá ActiveX ovládací prvek pomocí kolekce párových názvů a hodnot, které specifikují data perzistovaná ActiveX ovládacím prvkem.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na proudu, která nepodporuje inicializaci ActiveX ovládacího prvku do výchozího stavu.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na proudu, která podporuje inicializaci ActiveX ovládacího prvku do výchozího stavu.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Určuje, že ActiveX ovládací prvek je perzistován pomocí perzistence založené na úložišti.