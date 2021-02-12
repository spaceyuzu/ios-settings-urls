# Settings URLs

- Apple ID: `prefs:root=APPLE_ACCOUNT`
- Apple ID → Name, Phone Numbers, Email: `prefs:root=APPLE_ACCOUNT&path=APPLE_ACCOUNT_CONTACT`
- Apple ID → Password & Security: `prefs:root=APPLE_ACCOUNT&path=PASSWORD_AND_SECURITY`
- Apple ID → Payment & Shipping: `prefs:root=APPLE_ACCOUNT&path=PAYMENT_AND_SHIPPING`
- Apple ID → Subscriptions: `prefs:root=APPLE_ACCOUNT&path=SUBSCRIPTIONS`
- iCloud:
    - `prefs:root=CASTLE`
    - `prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE`
- iCloud → Keychain:
    - `prefs:root=CASTLE&path=com.apple.Dataclass.KeychainSync`
    - `prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/com.apple.Dataclass.KeychainSync`
- iCloud → iCloud Backup:
    - `prefs:root=CASTLE&path=BACKUP`
    - `prefs:root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP`
- iCloud → Find My: `prefs:root=APPLE_ACCOUNT&path=LOCATION_SHARING`
- iCloud → Family Sharing: `prefs:root=APPLE_ACCOUNT&path=FAMILY`
- Wi-Fi: `prefs:root=WIFI`
- Bluetooth: `prefs:root=Bluetooth`
- Cellular: `prefs:root=MOBILE_DATA_SETTINGS_ID`
- Cellular → Cellular Data Options: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR_DATA_OPTIONS`
- Cellular → Personal Hotspot: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=INTERNET_TETHERING`
- Cellular → Personal Hotspot → Wi-Fi Password: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=INTERNET_TETHERING/Wi-Fi%20Password`
- Cellular → Personal Hotspot → Family Sharing: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=INTERNET_TETHERING/Family%20Sharing`
- Cellular → Personal Hotspot → Family Sharing → [Family Member Name]: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=INTERNET_TETHERING/Family%20Sharing/[URL encoded family member name]`
- Cellular → System Services: `prefs:root=MOBILE_DATA_SETTINGS_ID&path=System%20Services`
- Personal Hotspot: `prefs:root=INTERNET_TETHERING`
- Personal Hotspot → Wi-Fi Password: `prefs:root=INTERNET_TETHERING&path=Wi-Fi%20Password`
- Personal Hotspot → Family Sharing: `prefs:root=INTERNET_TETHERING&path=Family%20Sharing`
- Personal Hotspot → Family Sharing → [Family Member Name]: `prefs:root=INTERNET_TETHERING&path=Family%20Sharing/[URL encoded family member name]`
- Notifications: `prefs:root=NOTIFICATIONS_ID`
- Notifications → specific app: `prefs:root=NOTIFICATIONS_ID&path=bundle.id.here`
- Notifications → Siri Suggestions: `prefs:root=NOTIFICATIONS_ID&path=Siri%20Suggestions`
- Sounds: `prefs:root=Sounds`
- Sounds → Ringtone: `prefs:root=Sounds&path=Ringtone`
- Sounds → Text Tone: `prefs:root=Sounds&path=Text_Messages`
- Sounds → New Voicemail: `prefs:root=Sounds&path=Voicemail`
- Sounds → New Mail: `prefs:root=Sounds&path=NEW_MAIL`
- Sounds → Sent Mail: `prefs:root=Sounds&path=SENT_MAIL`
- Sounds → Calendar Alerts: `prefs:root=Sounds&path=Calendar%20Alarm`
- Sounds → Reminder Alerts: `prefs:root=Sounds&path=Reminder%20Alerts`
- Sounds → AirDrop: `prefs:root=Sounds&path=AIRDROP`
- Do Not Disturb: `prefs:root=DO_NOT_DISTURB`
- Do Not Disturb → Allow Calls From: `prefs:root=DO_NOT_DISTURB&path=Allow%20Calls%20From`
- Do Not Disturb → Auto-Reply To: `prefs:root=DO_NOT_DISTURB&path=DRIVER_MODE_AUTOREPLY`
- Do Not Disturb → Auto-Reply: `prefs:root=DO_NOT_DISTURB&path=DRIVER_MODE_AUTOREPLY_MESSAGE`
- Screen Time: `prefs:root=SCREEN_TIME`
- Screen Time → Turn On Screen Time: `prefs:root=SCREEN_TIME&path=Turn%20On%20Screen%20Time`
- Screen Time → See All Activity: `prefs:root=SCREEN_TIME&path=SCREEN_TIME_SUMMARY`
- Screen Time → Downtime: `prefs:root=SCREEN_TIME&path=DOWNTIME`
- Screen Time → App Limits: `prefs:root=SCREEN_TIME&path=APP_LIMITS`
- Screen Time → Always Allowed: `prefs:root=SCREEN_TIME&path=ALWAYS_ALLOWED`
- Screen Time → Communication Limits: `prefs:root=SCREEN_TIME&path=COMMUNICATION_LIMITS`
- Screen Time → Content & Privacy Restrictions: `prefs:root=SCREEN_TIME&path=CONTENT_PRIVACY`
- General: `prefs:root=General`
- General → About: `prefs:root=General&path=About`
- General → About → SEID: `prefs:root=General&path=About/SEID`
- General → About → Certificate Trust Settings: `prefs:root=General&path=About/CERT_TRUST_SETTINGS`
- General → Software Update: `prefs:root=General&path=SOFTWARE_UPDATE_LINK`
- General → AirDrop: `prefs:root=General&path=AIRDROP_LINK`
- General → AirPlay & Handoff: `prefs:root=General&path=CONTINUITY_SPEC`
- General → CarPlay: `prefs:root=General&path=CARPLAY`
- General → iPhone/iPad Storage: `prefs:root=General&path=STORAGE_MGMT`
- General → iPhone/iPad Storage → [specific app]: `prefs:root=General&path=STORAGE_MGMT/[bundle id here]`
- General → Background App Refresh: `prefs:root=General&path=AUTO_CONTENT_DOWNLOAD`
- General → Background App Refresh → Background App Refresh: `prefs:root=General&path=AUTO_CONTENT_DOWNLOAD/AUTO_CONTENT_DOWNLOAD`
- General → Date & Time: `prefs:root=General&path=DATE_AND_TIME`
- General → Keyboard: `prefs:root=General&path=Keyboard`
- General → Keyboard → Keyboards: `prefs:root=General&path=Keyboard/KEYBOARDS`
- General ⇾ Keyboard ⇾ Hardware Keyboard: `prefs:root=General&path=Keyboard/Hardware%20Keyboard`
- General ⇾ Keyboard ⇾ Text Replacement: `prefs:root=General&path=Keyboard/USER_DICTIONARY`
- General ⇾ Keyboard ⇾ One Handed Keyboard: `prefs:root=General&path=Keyboard/ReachableKeyboard`
- General → Language & Region: `prefs:root=General&path=INTERNATIONAL`
- General → Language & Region → Device Language: `prefs:root=General&path=INTERNATIONAL/DEVICE_LANGUAGE`
- General → Language & Region → Calendar: `prefs:root=General&path=INTERNATIONAL/CALENDAR`
- General → Language & Region → Temperature Unit: `prefs:root=General&path=INTERNATIONAL/TEMPERATURE_UNIT`
- General → Dictionary: `prefs:root=General&path=DICTIONARY`
- General → VPN: `prefs:root=General&path=VPN`
- General → VPN → [VPN Configuration Name]: `prefs:root=General&path=VPN/[URL encoded VPN configuration name]`
- General → VPN → [VPN Configuration Name] → Delete VPN: `prefs:root=General&path=VPN/[URL encoded VPN configuration name]/Delete%20VPN`
- General → VPN → Add VPN Configuration…: `prefs:root=General&path=VPN/Add%20VPN%20Configuration%E2%80%A6`
- General → VPN → DNS: `prefs:root=General&path=VPN/DNS`
- General → Profiles: `prefs:root=General&path=ManagedConfigurationList`
- General → Profiles → Install Profile: `prefs:root=General&path=ManagedConfigurationList/PurgatoryInstallRequested`
- General → Reset: `prefs:root=General&path=Reset`
- Control Center: `prefs:root=ControlCenter`
- Control Center → Customize Controls: `prefs:root=ControlCenter&path=CUSTOMIZE_CONTROLS`
- Display: `prefs:root=DISPLAY`
- Display → Options: `prefs:root=DISPLAY&path=APPEARANCE_OPTIONS`
- Display → Night Shift: `prefs:root=DISPLAY&path=BLUE_LIGHT_REDUCTION`
- Display → Auto Lock: `prefs:root=DISPLAY&path=AUTOLOCK`
- Display → Text Size: `prefs:root=DISPLAY&path=TEXT_SIZE`
- Home Screen (iPhone): `prefs:root=HOME_SCREEN`
- Home Screen & Dock (iPad): `prefs:root=HOME_SCREEN_DOCK`
- Home Screen & Dock (iPad) → Multitasking: `prefs:root=HOME_SCREEN_DOCK&path=MULTITASKING`
- Accessibility: `prefs:root=ACCESSIBILITY`
- Accessibility → VoiceOver: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE`
- Accessibility → VoiceOver → Speech: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/SPEECH_TITLE`
- Accessibility → VoiceOver → Braille: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE`
- Accessibility → VoiceOver → Braille → Output: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/BrailleDisplayOutput`
- Accessibility → VoiceOver → Braille → Input: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/BrailleDisplayInput`
- Accessibility → VoiceOver → Braille → Braille Screen Input: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/BrailleGesturesInput`
- Accessibility → VoiceOver → Braille → Braille Tables: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/tableIdentifier`
- Accessibility → VoiceOver → Braille → Braille Tables → Language: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/tableIdentifier/DefaultLanguage`
- Accessibility → VoiceOver → Braille → Status Cells: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/BRAILLE_TITLE/STATUS_CELL`
- Accessibility → VoiceOver → Braille → Verbosity: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/VERBOSITY`
- Accessibility → VoiceOver → Braille → Verbosity → Punctuation: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/VERBOSITY/voiceOverPunctuationGroup`
- Accessibility → VoiceOver → Braille → Verbosity → Punctuation → Media Descriptions: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/VERBOSITY/voiceOverMediaDescriptions`
- Accessibility → VoiceOver → Audio: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/AUDIO_TITLE`
- Accessibility → VoiceOver → Commands: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/CUSTOMIZE_COMMANDS`
- Accessibility → VoiceOver → Activities: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/ACTIVITIES`
- Accessibility → VoiceOver → Activities → Programming: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/ACTIVITIES/Programming`
- Accessibility → VoiceOver → Activities → Add Activity...: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/ACTIVITIES/New`
- Accessibility → VoiceOver → Rotor: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/WEB_ROTOR`
- Accessibility → VoiceOver → Rotor Actions: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/ROTOR_ACTIONS`
- Accessibility → VoiceOver → Typing: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/TYPING_OPTIONS`
- Accessibility → VoiceOver → Typing → Typing Style: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/TYPING_OPTIONS/Typing%20Style`
- Accessibility → VoiceOver → Typing → Phonetic Feedback: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/TYPING_OPTIONS/Phonetic%20Feedback`
- Accessibility → VoiceOver → Typing → Modifier Keys: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/TYPING_OPTIONS/Modifier%20Keys`
- Accessibility → VoiceOver → Typing → Keyboard Interaction Time: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/TYPING_OPTIONS/Keyboard%20Interaction%20Time`
- Accessibility → VoiceOver → Navigate Images: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/INCLUDE_UNLABELED_IMAGES_TITLE`
- Accessibility → VoiceOver → Double-tap Timeout: `prefs:root=ACCESSIBILITY&path=VOICEOVER_TITLE/DOUBLE_TAP_INTERVAL_TITLE`
- Accessibility → Zoom: `prefs:root=ACCESSIBILITY&path=ZOOM_TITLE`
- Accessibility → Zoom → Keyboard Shortcuts: `prefs:root=ACCESSIBILITY&path=ZOOM_TITLE/ZoomKeyboardShortcuts`
- Accessibility → Zoom → Zoom Controller: `prefs:root=ACCESSIBILITY&path=ZOOM_TITLE/ZoomSlug`
- Accessibility → Zoom → Zoom Filter: `prefs:root=ACCESSIBILITY&path=ZOOM_TITLE/ZoomFilter`
- Accessibility → Magnifier: `prefs:root=ACCESSIBILITY&path=MAGNIFIER_TITLE`
- Accessibility → Display & Text Size: `prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT`
- Accessibility → Display & Text Size → Larger Text: `prefs:root=ACCESSIBILITY&path=DISPLAY_AND_TEXT/Larger%20Text`
- Accessibility → Motion: `prefs:root=ACCESSIBILITY&path=MOTION_TITLE`
- Accessibility → Spoken Content: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE`
- Accessibility → Spoken Content → Speech Controller: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE/SpeechController`
- Accessibility → Spoken Content → Customize Mouse Buttons: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE/SpeechController/CustomizeMouseButtons`
- Accessibility → Spoken Content → Highlight Content: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE/QuickSpeakHighlight`
- Accessibility → Spoken Content → Typing Feedback: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE/TypingFeedback`
- Accessibility → Spoken Content → Voices: `prefs:root=ACCESSIBILITY&path=SPEECH_TITLE/QuickSpeakAccents`
- Accessibility → Audio Descriptions: `prefs:root=ACCESSIBILITY&path=DESCRIPTIVE_VIDEO`
- Accessibility → Touch: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE`
- Accessibility → Touch → AssistiveTouch: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE`
- Accessibility → Touch → AssistiveTouch → Customize Top Level Menu: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchCustomize`
- Accessibility → Touch → AssistiveTouch → Single-Tap: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/Single-Tap`
- Accessibility → Touch → AssistiveTouch → Idle Opacity: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/IdleOpacity`
- Accessibility → Touch → AssistiveTouch → Devices: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchMouseDevices`
- Accessibility → Touch → AssistiveTouch → Devices → Bluetooth Devices...: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchMouseDevices/Bluetooth%20Devices%E2%80%A6`
- Accessibility → Touch → AssistiveTouch → Mouse Keys: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/AssistiveTouchMouseKeys`
- Accessibility → Touch → AssistiveTouch → Pointer Style: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/ASTMousePointerCustomization`
- Accessibility → Touch → AssistiveTouch → Pointer Style → Color: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/ASTMousePointerCustomization/Color`
- Accessibility → Touch → AssistiveTouch → Pointer Style → Color → Customize Mouse Buttons: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/ASTMousePointerCustomization/Color/CustomizeMouseButtons`
- Accessibility → Touch → AssistiveTouch → Pointer Style → Auto-Hide: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/ASTMousePointerCustomization/Auto-Hide`
- Accessibility → Touch → AssistiveTouch → Movement Tolerance: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/AIR_TOUCH_TITLE/Movement%20Tolerance`
- Accessibility → Touch → Force/Haptic Touch: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/ForceTouch`
- Accessibility → Touch → Touch Accommodations: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/Touch%20Accommodations`
- Accessibility → Touch → Call Audio Routing: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING`
- Accessibility → Touch → Call Audio Routing → Auto-Answer Calls: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/CALL_AUDIO_ROUTING/callAudioRoutingAutoAnswer`
- Accessibility → Touch → Back Tap: `prefs:root=ACCESSIBILITY&path=TOUCH_REACHABILITY_TITLE/Back%20Tap`
- Accessibility → Face ID & Attention: `prefs:root=ACCESSIBILITY&path=Face%20ID%20%26%20Attention`
- Accessibility → Switch Control: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle`
- Accessibility → Switch Control → Switches: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/SwitchesIdentifier`
- Accessibility → Switch Control → Switches → Bluetooth Devices...: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/SwitchesIdentifier/BluetoothDevicesIdentifier`
- Accessibility → Switch Control → Scanning Style: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Scanning%20Style`
- Accessibility → Switch Control → Pause on First Item: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Pause%20on%20First%20Item`
- Accessibility → Switch Control → Move Repeat: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Move%20Repeat`
- Accessibility → Switch Control → Long Press: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Long%20Press`
- Accessibility → Switch Control → Tap Behavior: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Tap%20Behavior`
- Accessibility → Switch Control → Focused Item After Tap: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Focused%20Item%20After%20Tap`
- Accessibility → Switch Control → Hold Duration: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Hold%20Duration`
- Accessibility → Switch Control → Ignore Repeat: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Ignore%20Repeat`
- Accessibility → Switch Control → Gliding Cursor: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/Gliding%20Cursor`
- Accessibility → Switch Control → [unidentified item]: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CameraPointPickerSwitch`
- Accessibility → Switch Control → Speech: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/SpeechIdentifier`
- Accessibility → Switch Control → Speech → Voices: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/SpeechIdentifier/VoicesIdentifier`
- Accessibility → Switch Control → Menu Items: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier`
- Accessibility → Switch Control → Menu Items → Top Level: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier/Top%20Level`
- Accessibility → Switch Control → Menu Items → Gestures: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier/Gestures`
- Accessibility → Switch Control → Menu Items → Device: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier/Device`
- Accessibility → Switch Control → Menu Items → Settings: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier/Settings`
- Accessibility → Switch Control → Menu Items → Media Controls: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomizeMenuIdentifier/Media%20Controls`
- Accessibility → Switch Control → Saved Gestures: `prefs:root=ACCESSIBILITY&path=ScannerSwitchTitle/CustomGesturesIdentifier`
- Accessibility → Voice Control: `prefs:root=ACCESSIBILITY&path=CommandAndControlTitle`
- Accessibility → Voice Control → Language: `prefs:root=ACCESSIBILITY&path=CommandAndControlTitle/LANGUAGE`
- Accessibility → Voice Control → Customize Commands: `prefs:root=ACCESSIBILITY&path=CommandAndControlTitle/CUSTOMIZE_COMMANDS`
- Accessibility → Voice Control → Vocabulary: `prefs:root=ACCESSIBILITY&path=CommandAndControlTitle/VOCABULARY`
- Accessibility → Voice Control → Overlay: `prefs:root=ACCESSIBILITY&path=CommandAndControlTitle/ALWAYS_SHOW_OVERLAY`
- Accessibility → Home Button: `prefs:root=ACCESSIBILITY&path=HOME_CLICK_TITLE`
- Accessibility → Apple TV Remote: `prefs:root=ACCESSIBILITY&path=Apple%20TV%20Remote`
- Accessibility → Keyboards: `prefs:root=ACCESSIBILITY&path=KEYBOARDS`
- Accessibility → Keyboards → Full Keyboard Access: `prefs:root=ACCESSIBILITY&path=KEYBOARDS/Full%20Keyboard%20Access`
- Accessibility → Keyboards → Key Repeat: `prefs:root=ACCESSIBILITY&path=KEYBOARDS/KEY_REPEAT`
- Accessibility → Keyboards → Sticky Keys: `prefs:root=ACCESSIBILITY&path=KEYBOARDS/STICKY_KEYS`
- Accessibility → Keyboards → Slow Keys: `prefs:root=ACCESSIBILITY&path=KEYBOARDS/SLOW_KEYS`
- Accessibility → Hearing Devices: `prefs:root=ACCESSIBILITY&path=HEARING_AID_TITLE`
- Accessibility → Sound Recognition: `prefs:root=ACCESSIBILITY&path=SOUND_RECOGNITION_TITLE`
- Accessibility → Sound Recognition → Sounds: `prefs:root=ACCESSIBILITY&path=SOUND_RECOGNITION_TITLE/Sounds`
- Accessibility → RTT: `prefs:root=ACCESSIBILITY&path=RTT`
- Accessibility → Audio/Visual: `prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE`
- Accessibility → Subtitles & Captioning: `prefs:root=ACCESSIBILITY&path=SUBTITLES_CAPTIONING`
- Accessibility → Guided Access: `prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE`
- Accessibility → Guided Access → Passcode Settings: `prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessSecurityLinkList`
- Accessibility → Guided Access → Time Limits: `prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList`
- Accessibility → Guided Access → Time Limits → Sound: `prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessTimeRestrictionsLinkList/GUIDED_ACCESS_TIME_RESTRICTIONS_SOUND_TITLE`
- Accessibility → Guided Access → Display Auto-Lock: `prefs:root=ACCESSIBILITY&path=GUIDED_ACCESS_TITLE/GuidedAccessAutoLockTime`
- Accessibility → Siri: `prefs:root=ACCESSIBILITY&path=SIRI_SETTINGS_TITLE`
- Accessibility → Accessibility Shortcut: `prefs:root=ACCESSIBILITY&path=TRIPLE_CLICK_TITLE`
- Wallpaper: `prefs:root=Wallpaper`
- Siri:
    - `prefs:root=SIRI`
    - `prefs-siri-shortcuts:root`
- Siri → Language: `prefs:root=SIRI&path=LANGUAGE_ID`
- Siri → Voice: `prefs:root=SIRI&path=VOICE_ID`
- Siri → Siri Responses: `prefs:root=SIRI&path=VOICE_FEEDBACK_ID`
- Siri → Siri & Dictation History: `prefs:root=SIRI&path=HISTORY`
- Siri → [specific app]: `prefs:root=SIRI&path=[bundle ID]`
- Apple Pencil: `prefs:root=Pencil`
- Face/Touch ID & Passcode: `prefs:root=PASSCODE`
- Face/Touch ID & Passcode → Require Passcode: `prefs:root=PASSCODE&path=PASSCODE_REQ`
- Emergency SOS: `prefs:root=EMERGENCY_SOS`
- Exposure Notifications: `prefs:root=EXPOSURE_NOTIFICATION`
- Battery: `prefs:root=BATTERY_USAGE`
- Battery → Battery Health: `prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH`
- Privacy: `prefs:root=Privacy`
- Privacy → Location Services: `prefs:root=Privacy&path=LOCATION`
- Privacy → Location Services → Share My Location: `prefs:root=Privacy&path=LOCATION/LOCATION_SHARING`
- Privacy → Location Services → Share My Location → [Family Member Name]: `prefs:root=Privacy&path=LOCATION/LOCATION_SHARING/[URl encoded family member name]`
- Privacy → Location Services → [specific app]: `prefs:root=Privacy&path=LOCATION/[bundle ID]`
- Privacy → Location Services → System Services: `prefs:root=Privacy&path=LOCATION/SYSTEM_SERVICES`
- Privacy → Tracking: `prefs:root=Privacy&path=USER_TRACKING`
- Privacy → Contacts: `prefs:root=Privacy&path=CONTACTS`
- Privacy → Calendars: `prefs:root=Privacy&path=CALENDARS`
- Privacy → Reminders: `prefs:root=Privacy&path=REMINDERS`
- Privacy → Photos: `prefs:root=Privacy&path=PHOTOS`
- Privacy → Photos → [specific app]: `prefs:root=Privacy&path=PHOTOS/[bundle ID]`
- Privacy → Bluetooth: `prefs:root=Privacy&path=BT_PERIPHERAL`
- Privacy → Local Network: `prefs:root=Privacy&path=LOCAL_NETWORK`
- Privacy → Microphone: `prefs:root=Privacy&path=MICROPHONE`
- Privacy → Speech Recognition: `prefs:root=Privacy&path=SPEECH_RECOGNITION`
- Privacy → Camera: `prefs:root=Privacy&path=CAMERA`
- Privacy → Health: `prefs:root=Privacy&path=HEALTH`
- Privacy → HomeKit: `prefs:root=Privacy&path=WILLOW`
- Privacy → Media & Apple Music: `prefs:root=Privacy&path=MEDIALIBRARY`
- Privacy → Motion & Fitness: `prefs:root=Privacy&path=MOTION`
- Privacy → Analytics & Improvements: `prefs:root=Privacy&path=PROBLEM_REPORTING`
- Privacy → Advertising: `prefs:root=Privacy&path=ADVERTISING`
- App Store: `prefs:root=STORE`
- App Store → App Downloads: `prefs:root=STORE&path=App%20Downloads`
- App Store → Video Autoplay: `prefs:root=STORE&path=Video%20Autoplay`
- Wallet: `prefs:root=PASSBOOK`
- Wallet → Add Card: `prefs:root=PASSBOOK&path=Add%20Card`
- Passwords (iOS 14): `prefs:root=PASSWORDS`
- Passwords & Accounts: `prefs:root=ACCOUNTS_AND_PASSWORDS`
- Passwords & Accounts → Add Account: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT`
- Passwords & Accounts → Add Account → iCloud: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/iCloud`
- Passwords & Accounts → Add Account → Google: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/Gmail`
- Passwords & Accounts → Add Account → AOL: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/AOL`
- Passwords & Accounts → Add Account → Outlook: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/Outlook`
- Passwords & Accounts → Add Account → Other: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER`
- Passwords & Accounts → Add Account → Other → Add Mail Account: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER/Add%20Mail%20Account`
- Passwords & Accounts → Add Account → Other → Add LDAP Account: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER/Add%20LDAP%20Account`
- Passwords & Accounts → Add Account → Other → Add CardDAV Account: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER/Add%20CardDAV%20Account`
- Passwords & Accounts → Add Account → Other → Add CalDAV Account: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER/Add%20CalDAV%20Account`
- Passwords & Accounts → Add Account → Other → Add Subscribed Calendar: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT/OTHER/Add%20Subscribed%20Calendar`
- Passwords & Accounts → Fetch New Data: `prefs:root=ACCOUNTS_AND_PASSWORDS&path=FETCH_NEW_DATA`
- Mail: `prefs:root=MAIL`
- Mail → Notifications: `prefs:root=MAIL&path=NOTIFICATIONS`
- Mail → Preview: `prefs:root=MAIL&path=Preview`
- Mail → Swipe Options: `prefs:root=MAIL&path=Swipe%20Options`
- Mail → Swipe Options → Swipe Left: `prefs:root=MAIL&path=Swipe%20Options/Swipe%20Left`
- Mail → Swipe Options → Swipe Right: `prefs:root=MAIL&path=Swipe%20Options/Swipe%20Right`
- Mail → Blocked: `prefs:root=MAIL&path=Blocked`
- Mail → Muted Thread Action: `prefs:root=MAIL&path=Muted%20Thread%20Action`
- Mail → Blocked Sender Options: `prefs:root=MAIL&path=Blocked%20Sender%20Options`
- Mail → Mark Addresses: `prefs:root=MAIL&path=Mark%20Addresses`
- Mail → Increase Quote Level: `prefs:root=MAIL&path=Increase%20Quote%20Level`
- Mail → Include Attachments with Replies: `prefs:root=MAIL&path=Include%20Attachments%20with%20Replies`
- Mail → Signature: `prefs:root=MAIL&path=Signature`
- Mail → Default Account: `prefs:root=MAIL&path=Default%20Account`
- Contacts: `prefs:root=CONTACTS`
- Contacts → Siri & Search: `prefs:root=CONTACTS&path=SIRI_AND_SEARCH`
- Contacts → Sort Order: `prefs:root=CONTACTS&path=ContactsSortOrder`
- Contacts → Display Order: `prefs:root=CONTACTS&path=PersonNameOrder`
- Contacts → Short Name: `prefs:root=CONTACTS&path=PersonShortName`
- Contacts → My Info: `prefs:root=CONTACTS&path=MeCard`
- Calendar: `prefs:root=CALENDAR`
- Calendar → Siri & Search: `prefs:root=CALENDAR&path=SIRI_AND_SEARCH`
- Calendar → Time Zone Override: `prefs:root=CALENDAR&path=TimeZoneCityArray`
- Calendar → Alternate Calendars: `prefs:root=CALENDAR&path=Alternate%20Calendars`
- Calendar → Sync: `prefs:root=CALENDAR&path=Sync`
- Calendar → Default Alert Times: `prefs:root=CALENDAR&path=Default%20Alert%20Times`
- Calendar → Start Week On: `prefs:root=CALENDAR&path=com.apple.mobilecal`
- Calendar → Default Calendar: `prefs:root=CALENDAR&path=Default%20Calendar`
- Notes: `prefs:root=NOTES`
- Notes → Siri & Search: `prefs:root=NOTES&path=SIRI_AND_SEARCH`
- Notes → Default Account: `prefs:root=NOTES&path=Default%20Account`
- Notes → Password: `prefs:root=NOTES&path=Password`
- Notes → Sort Notes By: `prefs:root=NOTES&path=Sort%20Notes%20By`
- Notes → New Notes Start With: `prefs:root=NOTES&path=New%20Notes%20Start%20With`
- Notes → Sort Checked Items: `prefs:root=NOTES&path=Sort%20Checked%20Items`
- Notes → Lines & Grids: `prefs:root=NOTES&path=Lines%20%26%20Grids`
- Notes → Note Backgrounds: `prefs:root=NOTES&path=Note%20Backgrounds`
- Notes → Access Notes from Lock Screen: `prefs:root=NOTES&path=Access%20Notes%20from%20Lock%20Screen`
- Reminders: `prefs:root=REMINDERS`
- Reminders → Siri & Search: `prefs:root=REMINDERS&path=SIRI_AND_SEARCH`
- Reminders → Default List: `prefs:root=REMINDERS&path=DEFAULT_LIST`
- Voice Memos: `prefs:root=VOICE_MEMOS`
- Voice Memos → Siri & Search: `prefs:root=VOICE_MEMOS&path=SIRI_AND_SEARCH`
- Voice Memos → Clear Deleted: `prefs:root=VOICE_MEMOS&path=RCVoiceMemosRecentlyDeletedWindowKey`
- Voice Memos → Audio Quality: `prefs:root=VOICE_MEMOS&path=RCVoiceMemosAudioQualityKey`
- Phone: `prefs:root=Phone`
- Messages: `prefs:root=MESSAGES`
- FaceTime: `prefs:root=FACETIME`
- FaceTime → Siri & Search: `prefs:root=FACETIME&path=SIRI_AND_SEARCH`
- Safari: `prefs:root=SAFARI`
- Safari → AutoFill: `prefs:root=SAFARI&path=AUTO_FILL`
- Safari → Content Blockers: `prefs:root=SAFARI&path=CONTENT_BLOCKERS`
- Safari → Downloads: `prefs:root=SAFARI&path=DOWNLOADS`
- Safari → Close Tabs: `prefs:root=SAFARI&path=Close%20Tabs`
- Safari → Page Zoom: `prefs:root=SAFARI&path=Page%20Zoom`
- Safari → Request Desktop Website: `prefs:root=SAFARI&path=Request%20Desktop%20Website`
- Safari → Reader: `prefs:root=SAFARI&path=Reader`
- Safari → Camera: `prefs:root=SAFARI&path=Camera`
- Safari → Microphone: `prefs:root=SAFARI&path=Microphone`
- Safari → Location: `prefs:root=SAFARI&path=Location`
- News: `prefs:root=NEWS`
- News → Acknowledgements: `prefs:root=NEWS&path=Acknowledgements`
- Translate: `prefs:root=TRANSLATE`
- Maps: `prefs:root=MAPS`
- Maps → Driving & Navigation: `prefs:root=MAPS&path=Driving%20%26%20Navigation`
- Maps → Transit: `prefs:root=MAPS&path=Transit`
- Compass: `prefs:root=COMPASS`
- Measure: `prefs:root=MEASURE`
- Measure → Siri & Search: `prefs:root=MEASURE&path=SIRI_AND_SEARCH`
- Shortcuts: `prefs:root=SHORTCUTS`
- Shortcuts → Legal Notices: `prefs:root=SHORTCUTS&path=Legal%20Notices`
- Health: `prefs:root=HEALTH`
- Health → Siri & Search: `prefs:root=HEALTH&path=SIRI_AND_SEARCH`
- Home: `prefs:root=HOMEKIT`
- Music: `prefs:root=MUSIC`
- Music → Cellular Data: `prefs:root=MUSIC&path=com.apple.Music:CellularData`
- Music → Optimize Storage: `prefs:root=MUSIC&path=com.apple.Music:OptimizeStorage`
- Music → EQ: `prefs:root=MUSIC&path=com.apple.Music:EQ`
- Music → Volume Limit: `prefs:root=MUSIC&path=com.apple.Music:VolumeLimit`
- TV: `prefs:root=TVAPP`
- TV → Cellular: `prefs:root=TVAPP&path=com.apple.videos:VideosPlaybackQualityCellularSetting`
- TV → Wi-Fi: `prefs:root=TVAPP&path=com.apple.videos:VideosPlaybackQualitySetting`
- TV → Siri & Search: `prefs:root=TVAPP&path=SIRI_AND_SEARCH`
- TV → Video Definition: `prefs:root=TVAPP&path=com.apple.videos%3APreferredPurchaseResolution`
- Photos: `prefs:root=Photos`
- Photos → Cellular Data: `prefs:root=Photos&path=CellularDataLinkList`
- Camera: `prefs:root=CAMERA`
- Camera → Formats: `prefs:root=CAMERA&path=CameraFormatsSettingsList`
- Camera → Record Video: `prefs:root=CAMERA&path=Record%20Video`
- Camera → Record Slo-mo: `prefs:root=CAMERA&path=Record%20Slo-mo`
- Camera → Preserve Settings: `prefs:root=CAMERA&path=CameraPreserveSettingsSwitch`
- Books: `prefs:root=IBOOKS`
- Books → Siri & Search: `prefs:root=IBOOKS&path=SIRI_AND_SEARCH`
- Books → Skip Forward: `prefs:root=IBOOKS&path=BKAudioBookSkipForward`
- Books → Skip Back: `prefs:root=IBOOKS&path=BKAudioBookSkipBackward`
- Books → Acknowledgements: `prefs:root=IBOOKS&path=Acknowledgements`
- Podcasts: `prefs:root=com.apple.podcasts`
- Game Center: `prefs:root=GAMECENTER`
- Game Center → Add Friends: `prefs:root=GAMECENTER&path=Add%20Friends`
- Game Center → Terms and Conditions: `prefs:root=GAMECENTER&path=Terms%20and%20Conditions`
- TV Provider: `prefs:root=VIDEO_SUBSCRIBER`
- Developer: `prefs:root=DEVELOPER_SETTINGS`
- Developer → Instruments/Logging: `prefs:root=DEVELOPER_SETTINGS&path=DTInstrumentsSettings`
- Developer → Network Link Conditioner: `prefs:root=DEVELOPER_SETTINGS&path=NLC`
- Developer → Multipath Networking: `prefs:root=DEVELOPER_SETTINGS&path=MULTI_PATH_AGG`
- Developer → Fill Rate: `prefs:root=DEVELOPER_SETTINGS&path=FILL_RATE`
- Developer → Ad Refresh Rate: `prefs:root=DEVELOPER_SETTINGS&path=AD_REFRESH_RATE`
- Developer → TV Provider: `prefs:root=DEVELOPER_SETTINGS&path=VideoSubscriberAccountSettings`
- Settings For App…: `prefs:root=[bundle ID]`