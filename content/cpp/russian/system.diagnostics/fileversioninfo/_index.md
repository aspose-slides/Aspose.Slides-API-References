---
title: FileVersionInfo
second_title: Aspose.Slides для C++ справочника API
description: "Предоставляет информацию о версии файла. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или используя оператор new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1
url: /ru/system.diagnostics/fileversioninfo/
---
## FileVersionInfo класс

Provides information on file version. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileVersionInfo
```

## Методы

| Method | Description |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Получает поле версии продукта. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Получает информацию о версии файла; не реализовано. |

## Смотрите также

* Простейство [System::Diagnostics](../)
* Библиотека [Aspose.Slides](../../)