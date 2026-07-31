---
title: ConvertAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek Array baru dan mengisinya dengan elemen-elemen dari array yang ditentukan yang dikonversi ke tipe OutputType menggunakan delegasi konverter yang ditentukan.
type: docs
weight: 625
url: /id/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) metode

Membuat objek [Array](../) baru dan mengisinya dengan elemen-elemen dari array yang ditentukan yang dikonversi ke tipe **OutputType** menggunakan delegasi konverter yang ditentukan.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| InputType | Tipe elemen dari array input |
| OutputType | Tipe elemen dari array hasil |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Objek [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Objek Converter yang digunakan untuk mengubah setiap elemen dari array input menjadi nilai setara tipe **OutputType** |

### Nilai Kembali

Array baru yang berisi nilai-nilai tipe **OutputType** yang setara dengan nilai-nilai **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) metode

Membuat objek [Array](../) baru dan mengisinya dengan elemen-elemen dari array yang ditentukan yang dikonversi ke tipe **OutputType** menggunakan objek fungsi konverter yang ditentukan.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| InputType | Tipe elemen dari array input |
| OutputType | Tipe elemen dari array hasil |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Objek [Array](../) |
| converter | std::function\<OutputType(InputType)> | Objek fungsi yang digunakan untuk mengubah setiap elemen dari array input menjadi nilai setara tipe **OutputType** |

### Nilai Kembali

Array baru yang berisi nilai-nilai tipe **OutputType** yang setara dengan nilai-nilai **input_array**

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Kelas [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)