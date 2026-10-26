---
title: PersistenceType
second_title: Справочник API Aspose.Slides для C++
description: Указывает метод, используемый для сохранения свойств ActiveX-контрола.
type: docs
weight: 6189
url: /ru/aspose.slides/persistencetype/
---
## PersistenceType перечисление

Указывает метод, используемый для сохранения свойств ActiveX control.

```cpp
enum class PersistenceType
```

### Values

| Имя | Значение | Описание |
| --- | --- | --- |
| NotDefined | -1 | Идентификатор persistance не указан. |
| PersistPropertyBag | 0 | Указывает, что ActiveX control сохраняется с использованием persistence на основе property-bag. Persistence на основе property-bag сохраняет ActiveX control с помощью коллекции пар имя-значение, которые указывают данные, сохраняемые ActiveX control. |
| PersistStream | 1 | Указывает, что ActiveX control сохраняется с использованием persistence на основе потока, который не поддерживает инициализацию ActiveX control в состояние по умолчанию. |
| PersistStreamInit | 2 | Указывает, что ActiveX control сохраняется с использованием persistence на основе потока, который поддерживает инициализацию ActiveX control в состояние по умолчанию. |
| PersistStorage | 3 | Указывает, что ActiveX control сохраняется с использованием persistence на основе хранилища. |

## См. также

* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)