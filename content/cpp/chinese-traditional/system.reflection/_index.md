---
title: "System::Reflection"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 755
url: /zh-hant/system.reflection/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) 類別描述組件。支援有限，因為 C# 與 C++ 的規則差異很大。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別封裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [AssemblyName](./assemblyname/) | 定義組件名稱。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別封裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | 單例，用於在執行中的組件中註冊類型。 |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | 單例註冊類型於執行中組件的基礎類型。 |
| [ConstructorInfo](./constructorinfo/) | 提供對建構函式中繼資料的存取。 |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | 如果模組中的任何類別無法載入，Module.GetTypes 方法會拋出 ReflectionTypeLoadException。切勿手動建立此類別的實例。請改用 ReflectionTypeLoadException 類別。切勿將 ReflectionTypeLoadException 類別的實例封裝至 [System::SmartPtr](../system/smartptr/)。 |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | 透過反射呼叫的方法若引發例外，會拋出 TargetInvocationException。切勿手動建立此類別的實例。請改用 TargetInvocationException 類別。切勿將 TargetInvocationException 類別的實例封裝至 [System::SmartPtr](../system/smartptr/)。 |
| [FieldInfo](./fieldinfo/) | 發現欄位的屬性並提供對欄位中繼資料的存取。 |
| [MemberInfo](./memberinfo/) | 提供成員的反射資訊。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別封裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [MethodBase](./methodbase/) | 方法的基礎資訊。此類別的物件只能使用 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別封裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。 |
| [MethodInfo](./methodinfo/) | 表示類別方法的資訊。 |
| [PropertyInfo](./propertyinfo/) | 表示屬性資訊。 |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [BindingFlags](./bindingflags/) | 定義成員與型別的查找模式與繫結。 |
| [FieldAttributes](./fieldattributes/) | 已反射的欄位屬性。 |
| [MemberTypes](./membertypes/) | 標記每種成員類型。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | 如果模組中的任何類別無法載入，Module.GetTypes 方法會拋出 ReflectionTypeLoadException。切勿將 ReflectionTypeLoadException 類別的實例封裝至 [System::SmartPtr](../system/smartptr/)。 |
| [TargetInvocationException](./targetinvocationexception/) | 透過反射呼叫的方法若引發例外，會拋出 TargetInvocationException。切勿將 TargetInvocationException 類別的實例封裝至 [System::SmartPtr](../system/smartptr/)。 |