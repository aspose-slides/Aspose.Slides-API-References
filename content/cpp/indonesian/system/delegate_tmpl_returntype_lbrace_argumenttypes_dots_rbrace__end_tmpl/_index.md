---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pointer ke fungsi, metode, atau objek fungsi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 287
url: /id/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> kelas

Mewakili sebuah pointer ke fungsi, metode, atau objek fungsi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../smartptr/) kelas untuk mengelola objek dari tipe ini.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ReturnType | Tipe nilai kembali dari fungsi, metode, atau objek fungsi yang ditunjuk oleh pointer yang diwakili oleh kelas |
| ArgumentTypes | Daftar argumen dari fungsi, metode, atau objek fungsi yang ditunjuk oleh pointer yang diwakili oleh kelas |

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [Delegate](./delegate/)() | Konstruktor default. Membuat objek delegate yang tidak menunjuk ke sesuatu apa pun. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Konstruktor salin bergerak. Mengambil kepemilikan entitas yang ditunjuk oleh delegate yang ditentukan. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Membuat objek delegate dari pointer yang ditentukan ke fungsi bebas atau metode statis. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Membuat delegate dari pointer yang ditentukan ke objek fungsi yang dihasilkan oleh std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Konstruktor. Membuat delegate dari objek fungsi yang ditentukan. |
|  [Delegate](./delegate/)(long, T\&&) | Konstruktor bergerak. Membuat delegate dari objek fungsi yang ditentukan. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Membuat delegate yang menunjuk ke metode non-statis yang ditentukan dari objek yang ditentukan. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Konstruktor. Membuat delegate yang menunjuk ke metode non-statis yang ditentukan dari objek yang ditentukan. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Membuat objek delegate yang menunjuk ke objek fungsi std::function. |
| **bool** [Empty](./empty/)() const | Menentukan apakah objek delegate saat ini kosong, misalnya tidak menunjuk ke entitas apa pun. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Memanggil fungsi, metode, atau objek fungsi yang ditunjuk oleh objek delegate saat ini. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operator penugasan bergerak. Mengambil kepemilikan entitas yang ditunjuk oleh delegate yang ditentukan. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Membandingkan dua objek delegate untuk memeriksa apakah mereka menunjuk ke entitas yang sama. |

## Catatan

```cpp
#include "system/delegate.h"
#include <iostream>

// Deklarasikan delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Tetapkan alamat fungsi PrintMessage ke variabel.
  Message mes = Message(&PrintMessage);

  // Panggil fungsi.
  mes();

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Hello, world!
*/
```

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)