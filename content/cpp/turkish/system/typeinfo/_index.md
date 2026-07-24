---
title: TypeInfo
second_title: Aspose.Slides için C++ API Referansı
description: Belirli bir tipi temsil eder ve onun hakkında bilgi sağlar.
type: docs
weight: 1379
url: /tr/system/typeinfo/
---
## TypeInfo sınıfı

Belirli bir tipi temsil eder ve onun hakkında bilgi sağlar.

```cpp
class TypeInfo
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Belirtilen özniteliği tipin öznitelik listesine ekler. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Tip T için varsayılan yapıcıyı ayarlar. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Sınıf örneğini oluşturan fonktör aracılığıyla varsayılan yapıcıyı ayarlar. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Belirtilen üyeyi tipin üye listesine ekler. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Birden fazla Boxed* sınıfı tarafından paylaşılacak **BoxedValue** tipi için benzersiz [TypeInfo](./) yapısını sağlar. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | UYGULANMADI. Geçerli nesnenin temsil ettiği tipin tanımlı olduğu derlemeye bir işaretçi döndürür. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | UYGULANMADI. Geçerli nesnenin temsil ettiği tipin derleme adı dahil tam nitelikli adını döndürür. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Temel tip tanımlayıcısını döndürür. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Geçerli Type nesnesinin henüz belirli tiplerle değiştirilmemiş tip parametreleri içerip içermediğini gösteren bir değer alır. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Belirtilen ada sahip üyelerin listesini alır. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Geçerli nesnenin temsil ettiği tipin (derleme adı olmadan) tam nitelikli adını döndürür. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Bu tip için genel tip bağımsız değişkenlerinin bir dizisini alır. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Tipin soyut olup olmadığını ve geçersiz kılınması gerektiğini gösteren bir değer alır. |
| **bool** [get_IsArray](./get_isarray/)() const | Tipin dizi olup olmadığını gösteren bir değer alır. |
| **bool** [get_IsClass](./get_isclass/)() const | Tipin sınıf veya delege olup olmadığını; yani değer tipi ya da arayüz olmadığını gösteren bir değer alır. |
| **bool** [get_IsEnum](./get_isenum/)() const | Geçerli Tipin bir enum olup olmadığını gösteren bir değer alır. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Geçerli Tipin, diğer genel tiplerin oluşturulabileceği bir genel tip tanımı olup olmadığını gösteren bir değer alır. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Tipin arayüz olup olmadığını; yani sınıf ya da değer tipi olmadığını gösteren bir değer alır. |
| **bool** [get_IsSealed](./get_issealed/)() const | Tipin sealed (kapatılmış) olarak ilan edilip edilmediğini gösteren bir değer alır. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Tipin değer tipi olup olmadığını gösteren bir değer alır. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Tipin derleme dışındaki kod tarafından erişilip erişilemeyeceğini gösteren bir değer alır. |
| [String](../string/) [get_Name](./get_name/)() const | Geçerli nesnenin temsil ettiği tipin adını döndürür. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Tipin ad alanını alır. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Belirtilen dizideki tiplerle eşleşen parametrelere sahip bir ortak örnek yapıcıyı arar. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Belirtilen BindingFlags kullanılarak geçerli Tip için tanımlı yapıcıları arar. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Geçerli Tip için tanımlı tüm ortak yapıcıları döndürür. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Belirtilen tipe sahip ve geçerli nesnenin temsil ettiği tipe uygulanmış özel özniteliği arar. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Tipe uygulanan tüm özel öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Tipe uygulanan belirli öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | UYGULANMADI. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Belirtilen bağlama kısıtlamalarını kullanarak belirtilen alanı arar. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Belirtilen bağlama kısıtlamalarını kullanarak geçerli Tip için tanımlı alanları arar. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Bu tip için genel tip bağımsız değişkenlerinin bir dizisini alır. |
| int [GetHashCode](./gethashcode/)() const | Bu örnek ile ilişkili bir hash kodu döndürür. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Geçerli Tip tarafından uygulanmış veya miras alınmış tüm arayüzleri alır. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Belirtilen ada sahip üyelerin listesini alır. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Belirtilen ada sahip yöntemi alır. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Geçerli Tipin tüm ortak özelliklerini döndürür. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Belirtilen bağlama kısıtlamalarını kullanarak geçerli Tipin özelliklerini arar. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Şablon parametresi tip tanımlayıcısını alır. |
| **uint32_t** [Hash](./hash/)() const | Geçerli nesnenin temsil ettiği tip ile ilişkili bir hash değeri döndürür. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Belirtilen tipin bir örneğinin geçerli tipin bir değişkenine atanıp atanamayacağını belirler. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | UYGULANMADI. Belirtilen tipin veya türetilmiş tiplerin bir veya daha fazla özniteliğinin bu üyeye uygulanıp uygulanmadığını gösterir. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Belirtilen nesnenin geçerli tipin bir örneği olup olmadığını belirler. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Geçerli nesnenin temsil ettiği tipin belirtilen sınıfın bir alt sınıfı olup olmadığını belirler. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Geçerli ve belirtilen [TypeInfo](./) nesnelerinin eşit olmadığını belirler. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Geçerli [TypeInfo](./) nesnesinin null nesne olmadığını, yani bir tipi temsil ettiğini belirler. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Geçerli ve belirtilen [TypeInfo](./) nesnelerinin eşit olup olmadığını belirler. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Geçerli [TypeInfo](./) nesnesinin null nesne olup olmadığını, yani herhangi bir tipi temsil etmediğini belirler. |
| void [reset](./reset/)() | [TypeInfo](./) değerini null olarak ayarlar. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Tipin değer tipi olup olmadığını gösteren bir değer ayarlar. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Temel tip tanımlayıcısını ayarlar. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Şablon parametresi tip tanımlayıcısını ayarlar. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Belirtilen string için hash hesaplar. |
| [String](../string/) [ToString](./tostring/)() const | Geçerli nesnenin temsil ettiği tipin adını içeren bir string döndürür. |
| static const [TypeInfo](./)\& [Type](./type/)() | [TypeInfo](./) sınıfını temsil eden bir [TypeInfo](./) nesnesi döndürür. |
|  [TypeInfo](./typeinfo/)() | Varsayılan yapıcı (tip ayarlanmamış). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null nesne yapıcısı (tip ayarlanmamış). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Yapıcı. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Yapıcı. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Yapıcı. |

## Alanlar

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | [TypeInfo](./)'nin boş listesini temsil eden sabit. |
| static [EmptyTypes](./emptytypes/) | [TypeInfo](./)'nin boş listesini temsil eden sabit. |

## Typedef'lar

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Tipi oluşturmak için fonksiyon işaretçisi. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)