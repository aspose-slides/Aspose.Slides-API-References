---
title: Delegate()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor default. Membuat objek delegate yang tidak menunjuk ke apa pun.
type: docs
weight: 1
url: /id/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metode


Konstruktor default. Membuat objek delegate yang tidak menunjuk ke apa pun.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metode




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metode


Konstruktor penyalinan pindahan. Mengambil kepemilikan entitas yang ditunjuk oleh delegate yang ditentukan.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | Delegate\&& | Objek Delegate untuk memindahkan entitas yang ditunjuk darinya |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metode


Konstruktor. Membuat objek delegate dari pointer yang ditentukan ke fungsi bebas atau metode statik.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe fungsi atau pointer metode statik yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| function | T | Pointer ke fungsi atau metode statik yang akan ditunjuk oleh instance Delegate yang baru dibuat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metode


Konstruktor. Membuat delegate dari pointer yang ditentukan ke objek fungsi yang dihasilkan oleh std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe objek fungsi yang dihasilkan oleh std::bind() yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| function | T | Pointer ke “bind expression” – sebuah pointer fungsi yang dihasilkan oleh std::bind() – yang akan ditunjuk oleh instance Delegate yang baru dibuat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metode


Konstruktor. Membuat delegate dari objek fungsi yang ditentukan.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe objek fungsi yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functor_tag | int | Nilai integer dummy; argumen ini digunakan untuk menyelesaikan ambiguitas |
| functor | T\& | Objek fungsi yang akan ditunjuk oleh delegate yang baru dibangun |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metode


Konstruktor pindahan. Membuat delegate dari objek fungsi yang ditentukan.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe objek fungsi yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functor_tag | long | Nilai integer dummy; argumen ini digunakan untuk menyelesaikan ambiguitas |
| functor | T\&& | Objek fungsi yang akan ditunjuk oleh delegate yang baru dibangun |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metode


Konstruktor. Membuat delegate yang menunjuk ke metode non-statis yang ditentukan pada objek yang ditentukan.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | tipe metode non-statis yang diterima konstruktor sebagai argumen |
| ClassType | tipe objek yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType ClassType::* | Pointer ke metode non-statis yang akan ditunjuk oleh delegate yang baru dibuat |
| obj | ClassType * | Pointer ke objek yang memiliki metode yang akan ditunjuk oleh delegate yang baru dibuat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metode


Konstruktor. Membuat delegate yang menunjuk ke metode non-statis yang ditentukan pada objek yang ditentukan.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | tipe metode non-statis yang diterima konstruktor sebagai argumen |
| ClassType | tipe objek yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType MemberClass::* | Pointer ke metode non-statis yang akan ditunjuk oleh delegate yang baru dibuat |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Pointer bersama ke objek yang memiliki metode yang akan ditunjuk oleh delegate yang baru dibuat |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metode


Membuat objek delegate yang menunjuk ke objek fungsi std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| R | tipe nilai kembali dari objek fungsi yang diterima konstruktor sebagai argumen |
| Args | daftar argumen dari objek fungsi yang diterima konstruktor sebagai argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Objek fungsi yang akan ditunjuk oleh objek delegate yang baru dibuat |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)