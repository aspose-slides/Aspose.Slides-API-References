---
title: FileInfo
second_title: Aspose.Slides for C++ API 参考
description: "表示指向文件的路径以及该路径所指的文件，并提供用于操作该文件的方法。该类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 274
url: /zh/system.io/fileinfo/
---
## FileInfo 类

表示指向文件的路径以及该路径指向的文件，并提供对其进行操作的方法。该类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，否则会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | 以 UTF-8 编码打开当前对象表示的文件进行文本写入，使用‘Append’模式且不共享。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | 将当前对象表示的文件复制到指定位置。如果目标文件已存在，复制将失败。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | 将当前对象表示的文件复制到指定位置。参数指定是否应覆盖已存在的目标文件。 |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | 在当前对象表示的路径指定的位置创建文件，并以截断模式打开进行读写，且不共享。 |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | 在当前对象表示的路径指定的位置创建文件，并以 UTF-8 编码打开进行文本写入，且不共享。 |
| void [Decrypt](./decrypt/)() | 未实现。 |
| void [Delete](./delete/)() override | 删除当前对象表示的文件。 |
| void [Encrypt](./encrypt/)() | 未实现。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，这里仍将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，这里仍将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | 构造一个表示指定文件的 [FileInfo](./) 类的新实例。 |
| virtual void [Finalize](../filesysteminfo/finalize/)() | 什么也不做。 |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | 返回当前对象表示的实体的属性。 |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | 以本地时间返回当前对象表示的实体的创建时间。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | 以 UTC 时间返回当前对象表示的实体的创建时间。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | 返回一个 [DirectoryInfo](../directoryinfo/) 对象，表示当前对象所表示文件所在的目录。 |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | 返回当前对象所表示的文件所在目录的完整名称。 |
| **bool** [get_Exists](./get_exists/)() override | 返回一个指示文件是否存在的值。 |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | 返回当前对象表示的文件的扩展名。 |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | 返回当前对象表示的实体的完整名称（包括路径）。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | 返回一个指示是否设置了 ReadOnly 属性的值。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | 以本地时间返回当前对象表示的实体的上次访问时间。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | 以 UTC 时间返回当前对象表示的实体的上次访问时间。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | 以本地时间返回当前对象表示的实体的上次写入时间。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | 以 UTC 时间返回当前对象表示的实体的上次写入时间。 |
| **int64_t** [get_Length](./get_length/)() | 返回文件的字节大小。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 返回文件的名称。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于对自定义对象进行哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。用于克隆自定义类型。 |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | 将当前对象表示的文件移动到指定位置。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | 以指定模式打开当前对象表示的文件进行读写，且不共享。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | 以指定模式打开当前对象表示的文件，使用指定的访问类型，且不共享。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 以指定模式打开当前对象表示的文件，使用指定的访问类型和共享选项。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | 仅以读取方式打开当前对象表示的文件，在 'Open' 模式下共享读取访问。 |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | 以 UTF-8 编码打开当前对象表示的路径所指向的已有文件进行文本读取，且不共享。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | 仅以写入方式打开当前对象表示的文件，在 'OpenOrCreate' 模式下且不共享。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| void [Refresh](../filesysteminfo/refresh/)() | 刷新当前对象的状态。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数按指定值递减。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 用当前 [FileInfo](./) 对象表示的文件内容替换指定目标文件的内容，并创建被替换文件的备份。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 用当前 [FileInfo](./) 对象表示的文件内容替换指定目标文件的内容，并创建被替换文件的备份。 |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | 设置当前对象表示的实体的指定属性。 |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | 以本地时间设置当前对象表示的实体的创建时间。 |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 时间设置当前对象表示的实体的创建时间。 |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | 设置或取消文件的 ReadOnly 属性。 |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | 以本地时间设置当前对象表示的实体的上次访问时间。 |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 时间设置当前对象表示的实体的上次访问时间。 |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | 以本地时间设置当前对象表示的实体的上次写入时间。 |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 以 UTC 时间设置当前对象表示的实体的上次写入时间。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 返回当前对象表示的路径。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [FileSystemInfo](../filesysteminfo/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)