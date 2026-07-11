---
title: PersistenceType
second_title: Aspose.Slides для Android через Java API
description: Определяет метод, используемый для сохранения свойств элемента управления ActiveX.
type: docs
url: /ru/com.aspose.slides/persistencetype/
---
**Наследование:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PersistenceType extends System.Enum
```

Указывает метод, используемый для хранения свойств элемента управления ActiveX.
## Поля

| Поле | Описание |
| --- | --- |
| [NotDefined](#NotDefined) | Идентификатор Persistance не указан. |
| [PersistPropertyBag](#PersistPropertyBag) | Указывает, что элемент управления ActiveX сохраняется с использованием property-bag-based persistence. |
| [PersistStream](#PersistStream) | Указывает, что элемент управления ActiveX сохраняется с использованием stream-based persistence, не поддерживающего инициализацию элемента управления ActiveX в состояние по умолчанию. |
| [PersistStreamInit](#PersistStreamInit) | Указывает, что элемент управления ActiveX сохраняется с использованием stream-based persistence, поддерживающего инициализацию элемента управления ActiveX в состояние по умолчанию. |
| [PersistStorage](#PersistStorage) | Указывает, что элемент управления ActiveX сохраняется с использованием storage-based persistence. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```

Идентификатор Persistance не указан.

### PersistPropertyBag {#PersistPropertyBag}
```
public static final int PersistPropertyBag
```

Указывает, что элемент управления ActiveX сохраняется с использованием property-bag-based persistence. Property-bag-based persistence хранит элемент управления ActiveX посредством коллекции пар «имя-значение», которые определяют данные, сохраняемые элементом управления ActiveX.

### PersistStream {#PersistStream}
```
public static final int PersistStream
```

Указывает, что элемент управления ActiveX сохраняется с использованием stream-based persistence, не поддерживающего инициализацию элемента управления ActiveX в состояние по умолчанию.

### PersistStreamInit {#PersistStreamInit}
```
public static final int PersistStreamInit
```

Указывает, что элемент управления ActiveX сохраняется с использованием stream-based persistence, поддерживающего инициализацию элемента управления ActiveX в состояние по умолчанию.

### PersistStorage {#PersistStorage}
```
public static final int PersistStorage
```

Указывает, что элемент управления ActiveX сохраняется с использованием storage-based persistence.