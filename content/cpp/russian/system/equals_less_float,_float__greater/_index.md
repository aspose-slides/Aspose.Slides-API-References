---
title: Equals< float, float >()
second_title: Aspose.Slides для C++ — справочник API
description: "Специализация для значений с плавающей запятой одинарной точности. Хотя два NaN с плавающей запятой определены в IEC 60559:1989 как всегда сравниваемые как неравные, контракт для System.Object.Equals требует, чтобы переопределения удовлетворяли требованиям оператора эквивалентности. Поэтому System.Double.Equals и System.Single.Equals возвращают True при сравнении двух NaN, в то время как оператор равенства возвращает False в этом случае, как того требует стандарт."
type: docs
weight: 2666
url: /ru/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) функция


Специализация для значений с плавающей запятой одинарной точности. Хотя два NaN с плавающей запятой определены в IEC 60559:1989 как всегда сравниваемые как неравные, контракт для [System.Object.Equals](../object/equals/) требует, чтобы переопределения удовлетворяли требованиям оператора эквивалентности. Поэтому System.Double.Equals и System.Single.Equals возвращают True при сравнении двух NaN, в то время как оператор равенства возвращает False в этом случае, как того требует стандарт.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const **float**\& | The first comparand |
| b | const **float**\& | The second comparand |

### Возвращаемое значение

True, если оба значения являются NaN или равны, иначе — false

## См. также

* Простейство имён [System](../)
* Библиотека [Aspose.Slides](../../)