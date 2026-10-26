---
title: "System::Net::Cache"
second_title: Aspose.Slides для C++ справочник API
description: 
type: docs
weight: 664
url: /ru/system.net.cache/
---
## Classes

| Класс | Описание |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | Политика кэширования HTTP, которая реализует семантику кэширования RFC2616. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [RequestCachePolicy](./requestcachepolicy/) | Общая политика кэширования запросов, используемая для кэширования [Http](../system.net.http/), FTP и т.д. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | Перечисление описывает параметры кэша, применимые к любому [WebRequest](../system.net/webrequest/). |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | Перечисление описывает параметры кэша для HTTP. |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl используется для указания предпочтений относительно возраста и актуальности кэшированного элемента. |