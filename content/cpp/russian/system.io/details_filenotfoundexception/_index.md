---
title: Details_FileNotFoundException
second_title: Aspose.Slides для C++ API Reference
description: "Исключение, которое выбрасывается, когда попытка доступа к файлу, не существующему на диске, не удаётся. Никогда не создавайте экземпляры этого класса вручную. Используйте вместо этого класс FileNotFoundException. Никогда не оборачивайте экземпляры класса FileNotFoundException в System::SmartPtr."
type: docs
weight: 183
url: /ru/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException класс

Исключение, которое выбрасывается, когда попытка доступа к файлу, не существующему на диске, не удаётся. Никогда не создавайте экземпляры этого класса вручную. Используйте класс FileNotFoundException вместо этого. Никогда не оборачивайте экземпляры класса FileNotFoundException в [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Получает имя файла, который вызывает это исключение. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Смотрите также

* Класс [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)