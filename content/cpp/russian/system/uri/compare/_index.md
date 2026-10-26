---
title: Compare()
second_title: Aspose.Slides для C++ API Reference
description: Сравнивает указанные объекты Uri с использованием заданных правил сравнения.
type: docs
weight: 521
url: /ru/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) метод


Сравнивает указанные объекты [Uri](../) с использованием заданных правил сравнения.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Первый сравниваемый |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Второй сравниваемый |
| partsToCompare | [UriComponents](../../uricomponents/) | Указывает части **uri1** и **uri2**, которые необходимо сравнить |
| compareFormat | [UriFormat](../../uriformat/) | Указывает экранирование символов, используемое при сравнении компонентов URI |
| comparisonType | [StringComparison](../../stringcomparison/) | Одно из значений StringComparison |

### Возвращаемое значение

Отрицательное значение, если **uri1** меньше **uri2**; 0, если uri1 и uri2 равны; положительное значение, если **uri1** больше **uri2**

## См. также

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)