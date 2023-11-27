# ignore

![Digital-Forensics-Process](https://github.com/thelocalh0st/randome-assets/assets/125783410/114e3480-85c7-4a51-9676-8abf2dd42c9f)

graph TD;
    style PluginTable fill:#f9f,stroke:#333,stroke-width:2px;
    style PluginTitle fill:#999,stroke:#fff,stroke-width:2px;
    style PluginRow fill:#fff,stroke:#666,stroke-width:2px;
    
    PluginTable --> PluginTitle;
    PluginTable --> PluginRow1;
    PluginTable --> PluginRow2;
    PluginTable --> PluginRow3;
    PluginTable --> PluginRow4;
    PluginTable --> PluginRow5;
    PluginTable --> PluginRow6;

    PluginTitle -->|Plugin Name|Function|Example|;

    PluginRow1 -->|winver|windows version|rip.exe -r C:\\Cases\\Analysis\\Registry\\SOFTWARE -p winver|;
    PluginRow2 -->|timezone|timezone|rip.exe -r C:\\Cases\\Analysis\\Registry\\SYSTEM -p timezone|;
    PluginRow3 -->|nic2|network info|rip.exe -r C:\\Cases\\Analysis\\Registry\\SYSTEM -p nic2|;
    PluginRow4 -->|networklist|list of APs|rip.exe -r C:\\Cases\\Analysis\\Registry\\SOFTWARE -p networklist|;
    PluginRow5 -->|shutdown|shutdown time|rip.exe -r C:\\Cases\\Analysis\\Registry\\SYSTEM -p shutdown|;
    PluginRow6 -->|defender|Windows defender details|rip.exe -r C:\\Cases\\Analysis\\Registry\\SOFTWARE -p defender|;
