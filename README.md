# HotkeyOSC
![Logo](https://github.com/murxylink/HotkeyOSC/blob/main/src/256.png)

This tool was made with [VVVV Gamma](https://github.com/vvvv) 6.6

Many thanks to the community for the video tutorials and NuGet that helped me create this application.

Additional NuGet's: [VL.IO.MouseKeyGlobal](https://github.com/bj-rn/VL.IO.MouseKeyGlobal), [VL.WinFormsUtils](https://github.com/domjancik/VL.WinFormsUtils)

Installer was made with [Inno Setup](https://github.com/jrsoftware/issrc).

## Functionality
You can emulate pressing any key on the system by sending its name via OSC. The application listens for a UDP packet with an OSC command on port ***5366***. 

OSC command address: 

> **/SimKB**

OSC argument type: 
> **s** (string utf-8 encoded)

## Supported keys list

    LButton
    RButton
    Cancel
    MButton
    XButton1
    XButton2
    Back
    Tab
    LineFeed
    Clear
    Return
    Enter
    ShiftKey
    ControlKey
    Menu
    Pause
    CapsLock
    Capital
    HangulMode
    HanguelMode
    KanaMode
    JunjaMode
    FinalMode
    HanjaMode
    KanjiMode
    Escape
    IMEConvert
    IMENonconvert
    IMEAccept
    IMEAceept
    IMEModeChange
    Space
    Prior
    PageUp
    PageDown
    Next
    End
    Home
    Left
    Up
    Right
    Down
    Select
    Print
    Execute
    Snapshot
    PrintScreen
    Insert
    Delete
    Help
    D0
    D1
    D2
    D3
    D4
    D5
    D6
    D7
    D8
    D9
    A
    B
    C
    D
    E
    F
    G
    H
    I
    J
    K
    L
    M
    N
    O
    P
    Q
    R
    S
    T
    U
    V
    W
    X
    Y
    Z
    LWin
    RWin
    Apps
    Sleep
    NumPad0
    NumPad1
    NumPad2
    NumPad3
    NumPad4
    NumPad5
    NumPad6
    NumPad7
    NumPad8
    NumPad9
    Multiply
    Add
    Separator
    Subtract
    Decimal
    Divide
    F1
    F2
    F3
    F4
    F5
    F6
    F7
    F8
    F9
    F10
    F11
    F12
    F13
    F14
    F15
    F16
    F17
    F18
    F19
    F20
    F21
    F22
    F23
    F24
    NumLock
    Scroll
    LShiftKey
    RShiftKey
    LControlKey
    RControlKey
    LMenu
    RMenu
    BrowserBack
    BrowserForward
    BrowserRefresh
    BrowserStop
    BrowserSearch
    BrowserFavorites
    BrowserHome
    VolumeMute
    VolumeDown
    VolumeUp
    MediaNextTrack
    MediaPreviousTrack
    MediaStop
    MediaPlayPause
    LaunchMail
    SelectMedia
    LaunchApplication1
    LaunchApplication2
    Oem1
    OemSemicolon
    Oemplus
    Oemcomma
    OemMinus
    OemPeriod
    OemQuestion
    Oem2
    Oemtilde
    Oem3
    OemOpenBrackets
    Oem4
    Oem5
    OemPipe
    OemCloseBrackets
    Oem6
    OemQuotes
    Oem7
    Oem8
    Oem102
    OemBackslash
    ProcessKey
    Packet
    Attn
    Crsel
    Exsel
    EraseEof
    Play
    Zoom
    NoName
    Pa1
    OemClear
    KeyCode
    Shift
    Control
    Alt
    Modifiers
