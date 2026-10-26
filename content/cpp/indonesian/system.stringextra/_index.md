---
title: "System::StringExtra"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 911
url: /id/system.stringextra/
---
## Fungsi

| Function | Deskripsi |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Menggabungkan array string. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Menggabungkan string. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Menggabungkan string. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Menggabungkan string. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk [SmartPtr](../system/smartptr/) tipe. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk tipe aritmetika. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Mengonversi beberapa objek menjadi string dan menggabungkan string yang dihasilkan. Spesialisasi untuk struktur dan tipe nilai lainnya. |