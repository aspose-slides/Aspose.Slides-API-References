---
title: "System::Collections::Specialized"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 391
url: /ru/system.collections.specialized/
---
## Классы

| Класс | Описание |
| --- | --- |
| [BitVector32](./bitvector32/) | Предоставляет простой лёгкий битовый вектор с простым целочисленным или [Boolean](../system/boolean/) доступом к 32-битному хранилищу. |
| [NameValueCollection](./namevaluecollection/) | Коллекция связанных [String](../system/string/) ключей и [String](../system/string/) значений, к которым можно получить доступ либо по ключу, либо по индексу. |
| [StringCollection](./stringcollection/) | Индексированный список строк. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [StringCollectionPtr](./stringcollectionptr/) | Указатель на коллекцию строк с оператором доступа. |
| [StringDictionary](./stringdictionary/) | [String](../system/string/) в словарь строк. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |

## Функции

| Функция | Описание |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(**BitVector32::Section**, **BitVector32::Section**) | Проверяет, равны ли два указанных объекта. |
| **bool** [operator!=](./operator_not_equal/)(**BitVector32::Section**, **BitVector32::Section**) | Проверяет, не равны ли два указанных объекта. |