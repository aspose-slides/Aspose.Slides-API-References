---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 287
url: /tr/system.boxedvaluedetail/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Comparable](./comparable/) | IComparable<> için basit bir uygulama |
| [NonComparable](./noncomparable/) | IComparable<> uygulanmayan kutulanmış tipler için taklit temel tür |

## Yapılar

| Yapı | Açıklama |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Kutu nesnesinin kendiliğinden belirtilen arayüzü uygulayıp uygulamadığını kontrol eden şablon koşulu. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) uygular [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Kutu nesnesinin kendiliğinden [IComparable](../system/icomparable/) arayüzünü uygulayıp uygulamadığını kontrol eden şablon koşulu. |

## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Belirtilen değerin eşitliğini [operator==()](../system/operator_equal_equal/) kullanarak belirler. |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Belirtilen değerin eşitliğini [System::Object::Equals()](../system/object/equals/) yöntemiyle belirler. |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | İki tek duyarlıklı kayan nokta değerini karşılaştırır. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | İki çift duyarlıklı kayan nokta değerini karşılaştırır. |