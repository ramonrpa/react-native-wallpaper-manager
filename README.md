# react-native-wallpaper-manager

Setar wallpaper usando react-native

## Install

    npm install --save https://github.com/ramonrpa/react-native-wallpaper-manager.git
  
## Link

    react-native link react-native-wallpaper-manager
  
## Como usar
    
    import WallPaperManager from 'react-native-wallpaper-manager';
    WallPaperManager.setWallPaper({uri: 'http://example.com/test.png', screen: 'both/home/lockscreen'}, (res)=> console.log(res));
  
  
