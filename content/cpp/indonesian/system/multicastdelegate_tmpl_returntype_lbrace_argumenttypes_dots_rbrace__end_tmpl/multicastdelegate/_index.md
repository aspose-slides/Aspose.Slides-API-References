---
title: MulticastDelegate()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat koleksi kosong.
type: docs
weight: 1
url: /id/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() metode

Membuat koleksi kosong.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) metode

Setara dengan konstruktor default.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) metode

Melakukan salinan dangkal dari koleksi delegasi.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| o | const MulticastDelegate\& | Sebuah instance dari kelas MulticastDelegate untuk menyalin koleksi delegasi dari. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) metode

Konstruktor pemindahan.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| o | MulticastDelegate\&& | Sebuah instance dari kelas MulticastDelegate untuk memindahkan koleksi delegasi dari. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) metode

Membuat sebuah instance dan menempatkan delegasi yang ditentukan ke dalam koleksi delegasi.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Sebuah delegasi untuk dimasukkan ke dalam koleksi delegasi |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) metode

Membuat sebuah instance dan menempatkan nilai yang ditentukan ke dalam koleksi delegasi.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe nilai yang akan dimasukkan ke dalam koleksi delegasi pada instance yang baru dibuat; tipe harus dapat dikonversi ke tipe Callback. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | Nilai yang akan dimasukkan ke dalam koleksi delegasi |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) metode

Membuat sebuah instance dan menempatkan nilai yang ditentukan ke dalam koleksi delegasi.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Nilai yang akan dimasukkan ke dalam koleksi delegasi |

## Lihat Juga

* Typedef [Callback](../callback/)
* Kelas [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)