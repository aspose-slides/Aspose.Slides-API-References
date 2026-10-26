---
title: "System::Security"
second_title: Aspose.Slides для C++ API Reference
description: 
type: docs
weight: 807
url: /ru/system.security/
---
## Классы

| Класс | Описание |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Secure string, представляет текст, который должен оставаться конфиденциальным. Этот класс НЕ ШИФРУЕТ внутренние данные. Экземпляры этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [SecureStringMarshal](./securestringmarshal/) | Набор методов для выделения и копирования неуправляемых блоков памяти. |
| [SecurityElement](./securityelement/) | XML-модель объекта для кодирования объекта безопасности. Не реализовано. Экземпляры этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
## Typedef

| Typedef | Описание |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) тип указателя. |