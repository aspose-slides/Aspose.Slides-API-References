---
title: disconnect()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus delegate yang ditentukan dari koleksi delegate.
type: docs
weight: 170
url: /id/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metode

Menghapus delegate yang ditentukan dari koleksi delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [Callback](../callback/) | The delegate to remove from the collection |

### Nilai Kembalian

Referensi ke diri sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metode

Menghapus metode non-statis yang ditentukan dari objek yang ditentukan dari koleksi delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | ClassType * | A pointer to an object member method of which is to be removed from the delegate collection |

### Nilai Kembalian

Referensi ke diri sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metode

Menghapus metode non-statis yang ditentukan dari objek yang ditentukan dari koleksi delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | A shared pointer to an object member method of which is to be removed from the delegate collection |

### Nilai Kembalian

Referensi ke diri sendiri

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metode

Menghapus objek MulticastDelegate yang ditentukan dari koleksi delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | An instance of the MulticastDelegate class to remove from the delegate collection |

### Nilai Kembalian

Referensi ke diri sendiri

## Lihat Juga

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)