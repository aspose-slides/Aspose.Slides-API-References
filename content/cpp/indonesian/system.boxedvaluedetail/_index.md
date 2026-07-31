---
title: "System::BoxedValueDetail"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 287
url: /id/system.boxedvaluedetail/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Comparable](./comparable/) | Implementasi sederhana dari IComparable<> |
| [NonComparable](./noncomparable/) | Tipe dasar tiruan untuk tipe kotak yang tidak mengimplementasikan IComparable<> |

## Struktur

| Struktur | Deskripsi |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predikat templat yang memeriksa apakah objek kotak harus mengimplementasikan antarmuka yang diberikan secara mandiri. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) mengimplementasikan [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predikat templat yang memeriksa apakah objek kotak harus mengimplementasikan antarmuka [IComparable](../system/icomparable/) secara mandiri. |

## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Menentukan kesetaraan nilai yang ditentukan menggunakan [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Menentukan kesetaraan nilai yang ditentukan menggunakan metode [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Membandingkan dua nilai floating-point presisi tunggal. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Membandingkan dua nilai floating-point presisi ganda. |