---
title: PersistenceType
second_title: Aspose.Slides pro Java API Reference
description: Specifikuje metodu používanou k ukládání vlastností ActiveX ovládacího prvku.
type: docs
url: /cs/com.aspose.slides/persistencetype/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Specifikuje metodu používanou k ukládání vlastností ActiveX control.
## Pole

| Pole | Popis |
| --- | --- |
| [NotDefined](#NotDefined) | ID perzistence není zadáno. |
| [PersistPropertyBag](#PersistPropertyBag) | Určuje, že ActiveX control je perzistován pomocí perzistence založené na property-bag. |
| [PersistStream](#PersistStream) | Určuje, že ActiveX control je perzistován pomocí perzistence založené na proudu, která nepodporuje inicializaci ActiveX control do výchozího stavu. |
| [PersistStreamInit](#PersistStreamInit) | Určuje, že ActiveX control je perzistován pomocí perzistence založené na proudu, která podporuje inicializaci ActiveX control do výchozího stavu. |
| [PersistStorage](#PersistStorage) | Určuje, že ActiveX control je perzistován pomocí perzistence založené na úložišti. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

ID perzistence není zadáno.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Určuje, že ActiveX control je perzistován pomocí perzistence založené na property-bag. Perzistence založená na property-bag ukládá ActiveX control pomocí kolekce párů název-hodnota, které specifikují data perzistovaná ActiveX control.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Určuje, že ActiveX control je perzistován pomocí perzistence založené na proudu, která nepodporuje inicializaci ActiveX control do výchozího stavu.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Určuje, že ActiveX control je perzistován pomocí perzistence založené na proudu, která podporuje inicializaci ActiveX control do výchozího stavu.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Určuje, že ActiveX control je perzistován pomocí perzistence založené na úložišti.