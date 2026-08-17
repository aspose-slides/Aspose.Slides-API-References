---
title: PersistenceType
second_title: Aspose.Slides для справочника API Java
description: Указывает метод, используемый для хранения свойств элемента управления ActiveX.
type: docs
url: /ru/com.aspose.slides/persistencetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Specifies the method used to store properties of the ActiveX control.
## Fields

| Field | Description |
| --- | --- |
| [NotDefined](#NotDefined) | Идентификатор постоянства не указан. |
| [PersistPropertyBag](#PersistPropertyBag) | Указывает, что элемент управления ActiveX сохраняется с использованием постоянства на основе контейнера свойств. |
| [PersistStream](#PersistStream) | Указывает, что элемент управления ActiveX сохраняется с использованием потокового постоянства, которое не поддерживает инициализацию элемента управления ActiveX в состояние по умолчанию. |
| [PersistStreamInit](#PersistStreamInit) | Указывает, что элемент управления ActiveX сохраняется с использованием потокового постоянства, которое поддерживает инициализацию элемента управления ActiveX в состояние по умолчанию. |
| [PersistStorage](#PersistStorage) | Указывает, что элемент управления ActiveX сохраняется с использованием постоянства на основе хранилища. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Идентификатор постоянства не указан.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Указывает, что элемент управления ActiveX сохраняется с использованием постоянства на основе контейнера свойств. Постоянство на основе контейнера свойств сохраняет элемент управления ActiveX с помощью коллекции пар имя-значение, которые определяют сохраняемые данные элемента управления ActiveX.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Указывает, что элемент управления ActiveX сохраняется с использованием потокового постоянства, которое не поддерживает инициализацию элемента управления ActiveX в состояние по умолчанию.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Указывает, что элемент управления ActiveX сохраняется с использованием потокового постоянства, которое поддерживает инициализацию элемента управления ActiveX в состояние по умолчанию.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Указывает, что элемент управления ActiveX сохраняется с использованием постоянства на основе хранилища.