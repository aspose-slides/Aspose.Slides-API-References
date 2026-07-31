---
title: Func
second_title: Referensi API Aspose.Slides untuk C++
description: "Delegasi fungsi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 859
url: /id/system/func/
---
## Func kelas


Delegasi fungsi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Args | Argumen panggilan, kemudian tipe balik wajib. |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  [Func](./func/)() | Konstruktor default yang membuat null-Func. |
|  [Func](./func/)(T\&&) | Konstruktor yang membangun objek [Func](./) dan menetapkan nilai (baik callback sebenarnya atau nullptr) padanya. |
|  [Func](./func/)(const [Func](./)\&) | Konstruktor salin. |
|  [Func](./func/)([Func](./)\&&) | Konstruktor pindah. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Penugasan salin. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Penugasan pindah. |
|  [~Func](./~func/)() | Destruktor. |
## Catatan



```cpp
#include "system/func.h"
#include <iostream"

// Fungsi ini menerima sebuah instance delegasi System::Func sebagai parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Buat sebuah instance delegasi System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Kirim instance yang dibuat sebagai argumen fungsi.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
1
4
9
*/
```

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)