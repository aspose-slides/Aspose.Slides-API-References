---
title: TypeInfo
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili tipe tertentu dan menyediakan informasi tentangnya.
type: docs
weight: 1379
url: /id/system/typeinfo/
---
## TypeInfo kelas

Mewakili tipe tertentu dan menyediakan informasi tentangnya.

```cpp
class TypeInfo
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Menambahkan atribut yang ditentukan ke daftar atribut tipe. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Menetapkan konstruktor default untuk tipe T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Menetapkan konstruktor default menggunakan funktor yang membuat instansi kelas. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Menambahkan anggota yang ditentukan ke daftar anggota tipe. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Menyediakan struktur [TypeInfo](./) unik untuk tipe **BoxedValue** yang dapat dibagikan oleh beberapa kelas Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NOT IMPLEMENTED. Mengembalikan pointer ke assembly di mana tipe yang direpresentasikan oleh objek saat ini dideklarasikan. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NOT IMPLEMENTED. Mengembalikan nama lengkap termasuk nama assembly dari tipe yang direpresentasikan oleh objek saat ini. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Mengembalikan deskriptor tipe dasar. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Mendapatkan nilai yang menunjukkan apakah objek Type saat ini memiliki parameter tipe yang belum digantikan oleh tipe spesifik. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Mendapatkan daftar anggota dengan nama yang ditentukan. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Mengembalikan nama lengkap (tanpa nama assembly) dari tipe yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Mendapatkan array argumen tipe generik untuk tipe ini. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Mendapatkan nilai yang menunjukkan apakah Type bersifat abstrak dan harus dioverride. |
| **bool** [get_IsArray](./get_isarray/)() const | Mendapatkan nilai yang menunjukkan apakah tipe tersebut adalah array. |
| **bool** [get_IsClass](./get_isclass/)() const | Mendapatkan nilai yang menunjukkan apakah Type adalah kelas atau delegate; yaitu, bukan tipe nilai atau antarmuka. |
| **bool** [get_IsEnum](./get_isenum/)() const | Mendapatkan nilai yang menunjukkan apakah Type saat ini merepresentasikan sebuah enumerasi. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Mendapatkan nilai yang menunjukkan apakah Type saat ini merepresentasikan definisi tipe generik, dari mana tipe generik lain dapat dibangun. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Mendapatkan nilai yang menunjukkan apakah Type adalah antarmuka; yaitu, bukan kelas atau tipe nilai. |
| **bool** [get_IsSealed](./get_issealed/)() const | Mendapatkan nilai yang menunjukkan apakah Type dideklarasikan sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Mendapatkan nilai yang menunjukkan apakah Type adalah tipe nilai. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Mendapatkan nilai yang menunjukkan apakah Type dapat diakses oleh kode di luar assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Mengembalikan nama tipe yang direpresentasikan oleh objek saat ini. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Mendapatkan ruang nama dari Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Mencari konstruktor instance publik yang parameternya cocok dengan tipe dalam array yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Mencari konstruktor yang didefinisikan untuk Type saat ini, menggunakan BindingFlags yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Mengembalikan semua konstruktor publik yang didefinisikan untuk Type saat ini. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Mencari atribut khusus yang diterapkan dengan tipe yang ditentukan dan diterapkan pada tipe yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Mengembalikan array yang berisi objek yang merepresentasikan semua atribut khusus yang diterapkan pada tipe. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Mengembalikan array yang berisi objek yang merepresentasikan atribut tertentu yang diterapkan pada tipe. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NOT IMPLEMENTED. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Mencari bidang yang ditentukan, menggunakan batasan binding yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Mencari bidang yang didefinisikan untuk Type saat ini, menggunakan batasan binding yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Mendapatkan array argumen tipe generik untuk tipe ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash yang terkait dengan instance ini. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Mendapatkan semua antarmuka yang diimplementasikan atau diwariskan oleh Type saat ini. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Mendapatkan daftar anggota dengan nama yang ditentukan. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Mendapatkan metode dengan nama yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Mengembalikan semua properti publik dari Type saat ini. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Mencari properti dari Type saat ini, menggunakan batasan binding yang ditentukan. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Mendapatkan deskriptor tipe parameter templat. |
| **uint32_t** [Hash](./hash/)() const | Mengembalikan nilai hash yang terkait dengan tipe yang direpresentasikan oleh objek saat ini. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Menentukan apakah sebuah instance dari tipe tertentu dapat ditetapkan ke variabel dengan tipe saat ini. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NOT IMPLEMENTED. Menunjukkan apakah satu atau lebih atribut dari tipe yang ditentukan atau tipe turunannya diterapkan pada anggota ini. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Menentukan apakah objek yang ditentukan adalah instance dari tipe saat ini. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Menentukan apakah tipe yang direpresentasikan oleh objek saat ini adalah subclass dari kelas yang ditentukan. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Menentukan apakah objek [TypeInfo](./) saat ini dan yang ditentukan tidak sama. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Menentukan apakah objek [TypeInfo](./) saat ini bukan objek null, yaitu ia merepresentasikan suatu tipe. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Menentukan apakah objek [TypeInfo](./) saat ini dan yang ditentukan sama. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Menentukan apakah objek [TypeInfo](./) saat ini adalah objek null, yaitu tidak merepresentasikan tipe apa pun. |
| void [reset](./reset/)() | Menetapkan [TypeInfo](./) ke null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Menetapkan nilai yang menunjukkan apakah Type adalah tipe nilai. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Menetapkan deskriptor tipe dasar. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Menetapkan deskriptor tipe parameter templat. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Menghitung hash untuk string yang ditentukan. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan string yang berisi nama tipe yang direpresentasikan oleh objek saat ini. |
| static const [TypeInfo](./)\& [Type](./type/)() | Mengembalikan objek [TypeInfo](./) yang merepresentasikan kelas [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Konstruktor default (tidak ada tipe yang disetel). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Konstruktor objek null (tidak ada tipe yang disetel). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstanta yang mewakili daftar kosong [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Konstanta yang mewakili daftar kosong [TypeInfo](./). |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Pointer fungsi untuk membangun tipe. |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)