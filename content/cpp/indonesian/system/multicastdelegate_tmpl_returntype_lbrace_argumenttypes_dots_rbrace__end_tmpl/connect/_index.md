---
title: connect()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan delegate yang ditentukan ke koleksi.
type: docs
weight: 144
url: /id/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metode

Menambahkan delegate yang ditentukan ke koleksi.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegate yang akan ditambahkan ke koleksi |

### Nilai Kembali

Referensi ke objek itu sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metode

Menambahkan objek fungsi yang ditentukan ke koleksi delegate. Objek fungsi tersebut dikonversi ke tipe delegate Callback sebelum ditambahkan ke koleksi.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| R | Tipe nilai kembali dari objek fungsi yang akan ditambahkan ke koleksi |
| Args | Daftar argumen dari objek fungsi yang akan ditambahkan ke koleksi |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Objek fungsi yang akan ditambahkan ke koleksi |

### Nilai Kembali

Referensi ke objek itu sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metode

Menambahkan objek MulticastDelegate yang ditentukan ke koleksi delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Sebuah instance dari kelas MulticastDelegate untuk ditambahkan ke koleksi delegate |

### Nilai Kembali

Referensi ke objek itu sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metode

Menambahkan metode non-statis yang ditentukan dari objek yang ditentukan ke koleksi delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | Tipe dari metode non-statis yang akan ditambahkan ke koleksi delegate |
| ClassType | Tipe objek yang metodenya akan ditambahkan ke delegate |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType ClassType::* | Pointer ke metode non-statis dari objek yang ditentukan |
| obj | ClassType * | Pointer ke objek anggota metode yang akan ditambahkan ke koleksi delegate |

### Nilai Kembali

Referensi ke objek itu sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metode

Menambahkan metode non-statis yang ditentukan dari objek yang ditentukan ke koleksi delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | Tipe dari metode non-statis yang akan ditambahkan ke koleksi delegate |
| ClassType | Tipe objek yang metodenya akan ditambahkan ke koleksi delegate |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType ClassType::* | Pointer ke metode non-statis dari objek yang ditentukan |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Pointer bersama ke objek anggota metode yang akan ditambahkan ke koleksi delegate |

### Nilai Kembali

Referensi ke objek itu sendiri

## Lihat Juga

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)