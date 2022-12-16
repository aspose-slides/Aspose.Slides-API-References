---
title: AudioFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/audioframe/
---

## AudioFrame class

  Represents an audio clip on a slide.
 

  The following examples shows how to change Audio Play Options.
  
```php
  $pres = new Presentation("AudioFrameEmbed_out.pptx");
  try {
    // Gets the AudioFrame shape
    $audioFrame = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    // Sets the Play mode to play on click
    $audioFrame->setPlayMode(AudioPlayModePreset.OnClick);
    // Sets the volume to Low
    $audioFrame->setVolume(AudioVolumeMode.Low);
    // Sets the audio to play across slides
    $audioFrame->setPlayAcrossSlides(true);
    // Disables loop for the audio
    $audioFrame->setPlayLoopMode(false);
    // Hides the AudioFrame during the slide show
    $audioFrame->setHideAtShowing(true);
    // Rewinds the audio to start after playing
    $audioFrame->setRewindAudio(true);
    // Saves the PowerPoint file to disk
    $pres->save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Methods

| Name | Description |
| --- | --- |
| [getAudioCdEndTrack](getaudiocdendtrack)() | Returns or sets a last track index Read/write int. |
| [getAudioCdEndTrackTime](getaudiocdendtracktime)() | Returns or sets a last track time. Read/write int. |
| [getAudioCdStartTrack](getaudiocdstarttrack)() | Returns or sets a start track index. Read/write int. |
| [getAudioCdStartTrackTime](getaudiocdstarttracktime)() | Returns or sets a start track time. Read/write int. |
| [getEmbedded](getembedded)() | Determines whether a sound is embedded to a presentation. Read-only boolean. |
| [getEmbeddedAudio](getembeddedaudio)() | Returns or sets embedded audio object. Read/write IAudio. |
| [getHideAtShowing](gethideatshowing)() | Determines whether an AudioFrame is hidden. Read/write boolean. |
| [getLinkPathLong](getlinkpathlong)() | Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String. |
| [getPlayAcrossSlides](getplayacrossslides)() | Determines whether audio is playing across the slides. Read/write boolean. |
| [getPlayLoopMode](getplayloopmode)() | Determines whether an audio is looped. Read/write boolean. |
| [getPlayMode](getplaymode)() | Returns or sets the audio play mode. Read/write AudioPlayModePreset. |
| [getRewindAudio](getrewindaudio)() | Determines whether audio is automatically rewinded to start after playing. Read/write boolean. |
| [getVolume](getvolume)() | Returns or sets the audio volume. Read/write AudioVolumeMode. |
| [setAudioCdEndTrack](setaudiocdendtrack)(int) | Returns or sets a last track index Read/write int. |
| [setAudioCdEndTrackTime](setaudiocdendtracktime)(int) | Returns or sets a last track time. Read/write int. |
| [setAudioCdStartTrack](setaudiocdstarttrack)(int) | Returns or sets a start track index. Read/write int. |
| [setAudioCdStartTrackTime](setaudiocdstarttracktime)(int) | Returns or sets a start track time. Read/write int. |
| [setEmbeddedAudio](setembeddedaudio)([Audio](../audio)) | Returns or sets embedded audio object. Read/write IAudio. |
| [setHideAtShowing](sethideatshowing)(boolean) | Determines whether an AudioFrame is hidden. Read/write boolean. |
| [setLinkPathLong](setlinkpathlong)(String) | Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String. |
| [setPlayAcrossSlides](setplayacrossslides)(boolean) | Determines whether audio is playing across the slides. Read/write boolean. |
| [setPlayLoopMode](setplayloopmode)(boolean) | Determines whether an audio is looped. Read/write boolean. |
| [setPlayMode](setplaymode)(int) | Returns or sets the audio play mode. Read/write AudioPlayModePreset. |
| [setRewindAudio](setrewindaudio)(boolean) | Determines whether audio is automatically rewinded to start after playing. Read/write boolean. |
| [setVolume](setvolume)(int) | Returns or sets the audio volume. Read/write AudioVolumeMode. |
