---
title: SetLicense()
second_title: Aspose.Slides for C++ API Reference
description: Licenses the component.
type: docs
weight: 14
url: /cpp/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) method


Licenses the component.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |
## Remarks



Tries to find the license in the following locations:

1. Explicit path.

2. The folder of the component assembly.

3. The folder of the client's calling assembly.

4. The folder of the entry assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licenses the component.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A stream that contains the license. |
## Remarks



Use this method to load a license from a stream.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [License](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)