---
title: STDIOStreamPositionPreference
second_title: Aspose.Slides для C++ справочник API
description: "Определяет, какая позиция в потоке предпочтительна в качестве общей позиции чтения и записи, когда std::basic_iostream и его потомки будут иметь разные позиции чтения и записи в момент создания обёртки."
type: docs
weight: 586
url: /ru/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum

Определяет, какая позиция в потоке предпочтительна в качестве общей позиции чтения и записи, когда std::basic_iostream и его потомки имеют разные позиции чтения и записи в момент создания обёртки.

```cpp
enum class STDIOStreamPositionPreference
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Zero | 0 | Zero позиция будет установлена как позиция чтения и записи. |
| ReadPosition | 1 | gptr позиция будет установлена как позиция чтения и записи. |
| WritePosition | 2 | pptr позиция будет установлена как позиция чтения и записи. |

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)