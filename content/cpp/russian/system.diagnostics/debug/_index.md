---
title: Debug
second_title: Справочник API Aspose.Slides для C++
description: Коллекция методов отладки, позволяющая отправлять отладочную информацию зарегистрированным слушателям. Все функции вывода работают только в Debug. Это статический тип без сервисов экземпляров. Никогда не следует создавать его экземпляры никакими способами.
type: docs
weight: 105
url: /ru/system.diagnostics/debug/
---
## Структура отладки

Коллекция методов отладки, позволяющая отправлять отладочную информацию зарегистрированным слушателям. Все функции вывода работают только в [Debug](./). Это статический тип без сервисов экземпляров. Никогда не следует создавать его экземпляры никакими способами.

```cpp
class Debug
```

## Методы

| Метод | Описание |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Проверяет условие и отправляет информацию при ошибке. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Проверяет условие и отправляет информацию при ошибке. |
| static void [Assert](./assert/)(**bool**, const char *) | Проверяет условие и отправляет информацию при ошибке. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Проверяет условие и отправляет информацию при ошибке. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Отправить сообщение об ошибке. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Получает статический список слушателей. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Печатает сообщение в отладочный интерфейс. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Печатает сообщение в отладочный интерфейс. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Записывает строку в отладочный интерфейс. |
| static void [Write](./write/)(const char_t *) | Записывает строку в отладочный интерфейс. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Записывает строку в отладочный интерфейс, если условие истинно. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Записывает строку в отладочный интерфейс. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Записывает строку в отладочный интерфейс. |
| static void [WriteLine](./writeline/)(const char_t *) | Записывает строку в отладочный интерфейс. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Записывает строку в отладочный интерфейс. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Записывает строку в отладочный интерфейс, если условие истинно. |

## См. также

* Пространство имён [System::Diagnostics](../)
* Библиотека [Aspose.Slides](../../)