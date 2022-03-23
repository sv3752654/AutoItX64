# AutoItX64
Activate the folder, select and open the first file Send("{TAB}") Sleep(500) Send("{DOWN}") Sleep(500) Send("{ENTER}") #include&lt;MsgBoxConstants.au3> #include &lt;WinAPIFiles.au3> ;Turn off redirection for a 32-bit script on 64-bit system. If @OSArch = "X64" And Not @AutoItX64 Then _WinAPI_Wow64EnableWow64FsRedirection(
