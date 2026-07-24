---
title: Nullable
second_title: Aspose.Slides için C++ API Referansı
description: İleri bildirim.
type: docs
weight: 1106
url: /tr/system/nullable/
---
## Nullable sınıf

İleri bildirim.

```cpp
template<typename T>class Nullable
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | The underlying value type which is extended by the [Nullable](./) class |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Mevcut nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere eşit olup olmadığını belirler. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Mevcut nesnenin herhangi bir değeri temsil edip etmediğini belirler. |
| T [get_Value](./get_value/)() const | Mevcut nesne tarafından temsil edilen değerin bir kopyasını döndürür. |
| int [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma (hash) kodu döndürür. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Mevcut nesne tarafından temsil edilen değeri, eğer mevcut nesne tarafından temsil edilen değer null ise belirtilen değerle döndürür. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Mevcut nesnenin null değerini temsil edip etmediğini belirler. |
| [Nullable](./nullable/)() | Null değerini temsil eden bir örnek oluşturur. |
| [Nullable](./nullable/)(std::nullptr_t) | Null değerini temsil eden bir örnek oluşturur. |
| [Nullable](./nullable/)(const T1\&) | [Nullable](./) sınıfının, belirtilen değeri (gerekirse) temel tip T değerine dönüştürülmüş şekilde temsil eden bir örnek oluşturur. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Belirtilen [Nullable](./) nesnesi tarafından temsil edilen bir değeri temsil eden bir örnek oluşturur. Belirtilen nullable nesne, oluşturulan örneğin temel tipinden farklı bir tipte değer temsil edebilir; bu durumda temsil edilen değer tip T'ye dönüştürülür. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Bu ve **other**'ın ikisinin de null olmamasını kontrol eden ve böyleyse bir lambda çağıran yardımcı işlev. Uygulamalarda kullanılır. |
| [operator const T &](./operator_const_t__and/)() const | Mevcut nesne tarafından temsil edilen değere sabit bir referans döndürür. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Mevcut nesne tarafından temsil edilen değerin null olmamasını belirler. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Mevcut nesne tarafından temsil edilen değerin belirtilen değere eşit olmamasını belirler. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Mevcut nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere eşit olmamasını belirler. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Belirtilen değeri sağ taraf argümanı olarak kullanarak [operator&=()](./operator_and_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Nullable<T> sınıfının varsayılan oluşturulmuş bir örneğini döndürür. |
| auto [operator+](./operator_plus/)(const T1\&) const | Nullable ve non-nullable değerleri toplar. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Nullable değerleri toplar. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Mevcut nesneyi null değeri temsil edecek şekilde sıfırlar. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Belirtilen değeri sağ taraf argümanı olarak kullanarak [operator+=()](./operator_plus_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Belirtilen [Nullable](./) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak [operator+=()](./operator_plus_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Nullable ve null işaretli değerleri çıkarır. |
| auto [operator-](./operator_minus/)(const T1\&) const | Nullable ve non-nullable değerleri çıkarır. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Nullable değerleri çıkarır. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | [Nullable](./) sınıfının null değeri temsil eden bir örneğini döndürür. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Belirtilen değeri sağ taraf argümanı olarak kullanarak [operator-=()](./operator_minus_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Belirtilen [Nullable](./) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak [operator-=()](./operator_minus_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Her zaman false döndürür. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Bu değerleri [operator<()](./operator_less/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değerden küçük olup olmadığını belirler. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Bu değerleri [operator<()](./operator_less/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değerden küçük olup olmadığını belirler. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Her zaman false döndürür. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Bu değerleri [operator<=()](./operator_less_equal/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değere küçük ya da eşit olup olmadığını belirler. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Bu değerleri [operator<=()](./operator_less_equal/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere küçük ya da eşit olup olmadığını belirler. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Mevcut nesneye null atar. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Nesnenin şu anda temsil ettiği değeri belirtilen değerle değiştirir. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Nesnenin şu anda temsil ettiği değeri belirtilen değerle değiştirir. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Mevcut nesne tarafından temsil edilen değerin null olup olmadığını belirler. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Mevcut nesne tarafından temsil edilen değerin belirtilen değere eşit olup olmadığını belirler. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Mevcut nesne tarafından temsil edilen değerin, belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere eşit olup olmadığını belirler. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Her zaman false döndürür. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Bu değerleri [operator>()](./operator_greater/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen değerden büyük olup olmadığını belirler. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Bu değerleri [operator>()](./operator_greater/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değerden büyük olup olmadığını belirler. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Her zaman false döndürür. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Bu değerleri [operator>=()](./operator_greater_equal/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen nesne tarafından temsil edilen değere büyük ya da eşit olup olmadığını belirler. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Bu değerleri [operator>=()](./operator_greater_equal/) uygulayarak, mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](./) nesnesi tarafından temsil edilen değere büyük ya da eşit olup olmadığını belirler. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Belirtilen değeri sağ taraf argümanı olarak kullanarak [operator|=()](./operator_or_equal/)'yi mevcut nesne tarafından temsil edilen değere uygular. |
| void [reset](./reset/)() | Şu anda temsil edilen değeri null olarak ayarlar. |
| void [set_Value](./set_value/)(const T\&) | Nullable nesneye yeni bir değer atar. |
| [String](../string/) [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen değeri string'e dönüştürür. |
## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | Bu sınıf tarafından temsil edilen değer tipinin bir takma adı. |
## Açıklamalar

Belirtilen tipte, null atanabilen bir değeri temsil eder. Bu tip yığıt (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipteki nesneleri yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

## Ayrıca Bakınız

* Namespace [System](../)
* Kütüphane [Aspose.Slides](../../)