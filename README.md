# Project-V
Read Me
Sonic Foundry, Inc. may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Sonic Foundry, Inc., the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.
Thank you for choosing Sonic Foundry Vegas. This document contains information about installing and using Vegas on your computer.
We've added many new features to Vegas Video 3.0.

You'll find information about Vegas’ new features in the online help and manual. In the online help, select the Contents tab. Double-click the Introduction book to open it and click the What's New in Vegas 3.0 topic. This topic lists many of the new features and provides links to the appropriate help topics.

•	DV batch capture, batch print-to-tape, clip detection, and project recapture
•	Project trimming/media consolidation
•	Intelligent rendering 
•	Dynamic RAM Previews
•	Dual-processor DV rendering support
•	Print-to-tape from the timeline
•	Create and edit Windows Media 8 (.wmv, wma) files, with Web metadata including closed captioning
•	On-the-fly web metadata arrangement (import existing script copy for streaming media closed captioning and place caption cues while playing)
•	New MPEG-1 and MPEG-2 encoding tools
•	Create and edit Windows Media 8 (.wmv) files
•	Smooth audio and video envelopes: a whole new sound and look
•	Smooth temporal and spatial keyframe control for motion and crop effects
•	Nine new video overlay modes for expanded compositing control
•	Five audio pan models, including constant power balance
•	Mono and channel swap/combine support for stereo audio files
•	Audio phase inversion for tracks and events
•	Frame quantize
•	Apply interlace filter
•	Framerate undersampling (strobing)
•	New titling and credit roll tools for pristine video text
•	New video effects: Lens Flare, Light Rays, Border, Film FX, Linear and Radial Blur, Mirror, Timecode Burn, and more
•	New image-correction filters: Color Curves, Black Restore, Levels, Unsharp Mask, and more
•	Voice-optimized timestretching
•	An a/v sychronization bug in MPEG encodes has been fixed.
•	A bug has been fixed that caused print-to-tape operations to fail when markers with no text were present.
•	In Vegas 3.0a and 3.0b, choosing None from the Time stretch / pitch shift Method drop-down list in the Audio Event Properties dialog had no effect on time-stretched audio events. This bug has been resolved.
•	A Vegas project saved in version 3.0b will not open in any previous version of Vegas.  Project structure had to be changed to address bugs and there was no way to avoid this project versioning incompatibility. 
•	Text command markers now embed captions in QuickTime streaming files for viewing in the QuickTime player.
•	RealMedia 9 video codecs are now available on the Advanced Video tab in the Custom Settings dialog. Standard templates continue to use RealMedia version 8 video codecs.   
•	A bug that caused some color curves settings to display inaccurrate color values has been corrected.
•	Autonamed CD extraction now correctly saves files to the Recorded Files folder.
•	Regions and markers and regions created in .w64 files using Sound Forge 6 now correctly display in the Vegas trimmer window.
•	PAL Widescreen DV renders now use correctly auto-switching format flag. 
•	A bug that prevented some resampled events from resampling when using the best render quality has been fixed.
•	A bug that caused play/pause in the Trimmer to revert to timeline focus has been corrected.
•	A bug that caused Vegas to crash during project loading when transitions were missing has been corrected.
•	A bug that caused disk-at-once CDs to cause problems with some third-party verification software has been corrected.
•	The Main Concept MPEG-2 DVD templates now have an average bitrate of 6,000,000.
•	Numerous Video Capture changes have also been implemented. Please see your Video Capture readme.
•	A bug that caused normalize to fail on looped clips has been corrected.
•	Vegas will use SoundForge 6.0 as its default audio editor if SoundForge 6.0 is installed on the system.
•	A bug that caused the Main Concept plug-in to crash when using K6 processors has been corrected.

	3.0 Known Issues
	
	Red Book CD Authoring
	
	On some computers running Windows XP, Vegas is unable to create Red Book CDs using the PlexWriter 24/10/40A CD burner. We are working with Plextor to resolve the issue.
	
	MPEG file encoding
	
	When you render separate audio and video streams, the encoder will create an .m1v (MPEG-1) or .m2v (MPEG-2) file for the video stream and an .mpa file for the audio stream. However, the rendering progress dialog will report that an .mpg file is being created.
	
	When rendering separate audio and video streams, Vegas will append a four-digit suffix to the file name if the target file exists. If the encoder exceeds [filename]9999.m2v or [filename]9999.mpa, encoding will fail and notify you that a file with the name already exists.
	
	For more information about the MPEG templates available in Vegas, please see “Rendering MPEG Files” in the online help.
	
	Project compatibility
	Vegas 3.0c can open projects you created in previous versions of Vegas. However, previous versions of Vegas Video cannot open Vegas 3.0c projects. If you need to work with a previous version of Vegas, please work with a copy of your project or use the Save As command to save your Vegas 3.0 project with a unique name. 
	
	Vegas Video 3.0 can also open your Sonic Foundry VideoFactory 1.0 and 2.0 projects.
	
	Vegas and Pixelan StepMotion and StepTime plug-ins
	If you are using the PixelanStepMotion or StepTime plug-ins, it is recommended that you set the Dynamic RAM Preview Max setting on the Video Preferences tab 0. This will ensure more accurate previews when using these specialized filters. Rendering is not affected when Dynamic RAM Preview is enabled.
	
	Downloading QuickTime for Windows
	You’ll need to install QuickTime for Windows in order to use TIFF files and render MOV files. Vegas does not include the QuickTime installer. This can be downloaded free of charge from Apple Computer, Inc. at http://www.apple.com.
	Important: Make sure you download and install the QuickTime Authoring Components.
	
	Windows Media Player and Real Player
  Sonic Foundry Vegas includes the many new encoding formats from Real and Microsoft. It is recommended that you update to the most current versions of Windows Media Player (www.microsoft.com), and Real Player (www.real.com) for optimal file playback compatibility.

	File size limitations (FAT32 and NTFS disk drives)
	AVI files larger than 2GB are supported by the OpenDML file standard, (also called "ODML" or "AVI version 2.0"). This means Vegas is limited only by your operating system and/or file system (how your drives are formatted). 
•	Drives formatted as FAT32 under Windows 98SE or Me allow files of up to 4GB. 
•	Drives formatted as NTFS under Windows 2000 and XP do not have a 4GB limit. 
	By default, Vegas creates OpenDML-compatible files. This allows you to render large AVI file sizes. Some other applications may not be ODML compatible and may not be able to use these files. To change the default behavior, go to the File menu, choose Render As and click the Custom button. Then, on the Video tab, clear the Create an OpenDML (AVI version 2.0) compatible file check box.
	
	Video Capture
	Sonic Foundry Video Capture is automatically installed with Vegas. You can start Video Capture from the Media Pool or File menu. 

	Some Sony computers with built in IEEE-1394 i-Link DV use a custom Sony DV driver that will need to be updated in order to get full functionality when using the Sonic Foundry Video Capture tool. Running the utility "SFSony.exe", which is included in the Extras folder on the CD or available at www.sonicfoundry.com/download/step2.asp?DID=223  will fix the problem. You can also use this utility to restore your original Sony settings.
	
	
	4.0 System Requirements
	The following lists the minimum system requirements for using Sonic Foundry Vegas:
•	Windows 98 SE, Windows ME, Windows 2000, or Windows XP 
•	400 MHz processor
•	Windows-compatible sound card
•	OHCI-compliant, IEEE-1394 DV card (for DV capture and print-to-tape)
•	40MB available hard disk space for installation
•	128MB RAM 
•	7200 RPM hard drive or faster 
•	Internet Explorer 4 or later (IE 5 installer included on CD)
•	DirectX 8.0 (Included on CD)

The install utility, VegasVideo3Install.exe, creates any necessary folders and copies all files required by Vegas to your computer.

Double-click the file after downloading, and follow the on-screen prompts to install the appropriate version of Vegas for your computer.

Vegas Video 3.0 can be installed without removing existing Vegas Video 2.0 installations.

Included on the Vegas CD is a complete Vegas User Manual in Adobe Acrobat (PDF) format. The Acrobat format allows easy printing of the text, should you need a hard copy. The manual is located in the Manuals folder on the CD. 
Manuals can also be downloaded from www.sonicfoundry.com/download   

Installing Adobe Acrobat Reader
In order to view the manual, you will need to install the Adobe Acrobat Reader. It has been included on the 

CD in the Extras folder for your convenience. To install Acrobat Reader, follow these steps:

1)	Place the Vegas CD in the drive. AutoPlay launches an installation menu. 
	
	Note: If you have disabled the CD-ROM AutoPlay feature, click the Start button and choose Run. Type D:\Extras\Acrobat Reader 4.0\English\ar40eng.exe, where D is the drive letter of your CD-ROM drive, and follow the on-screen prompts to complete the installation.
	
	
2)	Choose Browse, and then browse to the D:\Extras\Acrobat Reader 4.0\English\ folder.
3)	Double-click the ar40eng.exe icon and follow the on-screen prompts to complete the installation.

You can also download Adobe Acrobat Reader from www.sonicfoundry.com/download/step2.asp?DID=101

Your installation CD-ROM includes demo versions of other select products available from Sonic Foundry. To install a demo, run the main setup program on the root of the Vegas CD and choose Product Demos from the Install screen. Follow the links for the demo you want to install.

If you would like any more information or demos of other products from Sonic Foundry, please visit our Web site (www.sonicfoundry.com). You will always find the latest technical information, demos, and product announcements from Sonic Foundry there.

Commercial distribution of the Sonic Foundry demos requires written permission from Sonic Foundry.

Sonic Foundry can be contacted in the following ways:

Sonic Foundry, Inc.
1617 Sherman Ave.
Madison, Wisconsin  53704
USA

Customer Service is available to help you with pre-purchase questions, order processing, and registration/installation issues.
•	¬For a detailed list of Customer Service options, we encourage you to visit www.sonicfoundry.com.  
•	Telephone assistance during normal office hours:
	•	1-800-577-6642 (toll-free) in US, Canada, and Virgin Islands.
	•	+800-000-76642 (toll-free) in Australia, Denmark, France, Germany, Italy, Sweden, UK, Netherlands, and Japan.
	•	+608-204-7703 for all other countries.
•	E-mail: customerservice@sonicfoundry.com.
•	Fax: 1-608-250-1745.
	
	Technical Support:
•	For a detailed list of Technical Support options, we encourage you to visit www.sonicfoundry.com/support or call 608-256-5555.
•	The full version of Vegas Audio and Vegas Video include 60 days of complimentary phone support. For your complimentary support, please call 608-204-7704. Your complimentary support begins the day you register your product, and registration is required to obtain support.
•	E-mail: support@sonicfoundry.com.
•	Fax: 608-250-1745.
 
