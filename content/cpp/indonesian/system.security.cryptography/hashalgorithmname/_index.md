---
title: HashAlgorithmName
second_title: Referensi API Aspose.Slides untuk C++
description: "String yang merepresentasikan nama algoritma hash. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 755
url: /id/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct


[String](../../system/string/) yang merepresentasikan nama algoritma hash. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../../system/smartptr/) kelas untuk mengelola objek tipe ini.

```cpp
class HashAlgorithmName
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Create [HashAlgorithmName](./) from OID-value. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Gets a [HashAlgorithmName](./) representing [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Gets string representation of the algorithm name. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Gets a [HashAlgorithmName](./) representing [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Gets a [HashAlgorithmName](./) representing [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Gets a [HashAlgorithmName](./) representing [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Gets a [HashAlgorithmName](./) representing [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Constructor. |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | Gets string representation of the algorithm name. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Try to create [HashAlgorithmName](./) from OID-value. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Returns a [TypeInfo](../../system/typeinfo/) object that represent [TimeSpan](../../system/timespan/) structure. |
## Lihat Juga

* Ruang Nama [System::Security::Cryptography](../)
* Pustaka [Aspose.Slides](../../)