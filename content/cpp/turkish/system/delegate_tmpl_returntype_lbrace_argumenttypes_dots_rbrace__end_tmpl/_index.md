---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API Referansı
description: "Bir fonksiyon, metod veya fonksiyon nesnesine işaretçiyi temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değerle ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 287
url: /tr/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> sınıf


Bir fonksiyon, metod veya fonksiyon nesnesine işaretçi temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değerle ya da referansla geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu tipin nesnelerini yönetmek için asla kullanmayın.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ReturnType | Sınıf tarafından temsil edilen bir fonksiyon, metod veya fonksiyon nesnesi işaretçisinin dönüş tipi |
| ArgumentTypes | Sınıf tarafından temsil edilen bir fonksiyon, metod veya fonksiyon nesnesi işaretçisinin argüman listesi |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [Delegate](./delegate/)() | Varsayılan yapıcı. Herhangi bir şeye işaret etmeyen delege nesnesini oluşturur. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Taşıma kopya yapıcı. Belirtilen delegenin işaret ettiği varlığın sahipliğini alır. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Yapıcı. Belirtilen serbest fonksiyon ya da statik metoda işaret eden göstericiden bir delege nesnesi oluşturur. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Yapıcı. std::bind() tarafından oluşturulan fonksiyon nesnesine işaret eden göstericiden bir delege oluşturur. |
|  [Delegate](./delegate/)(int, T\&) | Yapıcı. Belirtilen fonksiyon nesnesinden bir delege oluşturur. |
|  [Delegate](./delegate/)(long, T\&&) | Taşıma yapıcı. Belirtilen fonksiyon nesnesinden bir delege oluşturur. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Yapıcı. Belirtilen nesnenin belirtilen statik olmayan metoduna işaret eden bir delege oluşturur. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Yapıcı. Belirtilen nesnenin belirtilen statik olmayan metoduna işaret eden bir delege oluşturur. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Bir std::function fonksiyon nesnesine işaret eden bir delege nesnesi oluşturur. |
| **bool** [Empty](./empty/)() const | Mevcut delege nesnesinin boş olup olmadığını belirler, örn. herhangi bir varlığa işaret etmiyorsa. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Mevcut delege nesnesinin işaret ettiği fonksiyon, metod veya fonksiyon nesnesini çağırır. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Taşıma atama operatörü. Belirtilen delegenin işaret ettiği varlığın sahipliğini alır. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | İki delege nesnesini karşılaştırarak aynı varlığa işaret edip etmediklerini kontrol eder. |
## Açıklamalar



```cpp
#include "system/delegate.h"
#include <iostream>

// Delegeyi bildir.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Değişkene PrintMessage fonksiyonunun adresini atayın.
  Message mes = Message(&PrintMessage);

  // Fonksiyonu çağır.
  mes();

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Hello, world!
*/
```

## Bakınız

* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)