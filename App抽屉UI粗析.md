# App抽屉UI粗析

NavigationUI.setupActionBarWithNavController(this, navController, mAppBarConfiguration);
监听和改变ActionBar上的标题和图标

NavigationUI.setupWithNavController(navigationView, navController);
左侧抽屉Item的切换

DrawerLayout
左侧抽屉父布局

NavigationView
左侧抽屉导航布局

activity\_main.xml
包含主界面app\_bar\_main.xml和左侧导航栏界面

app\_bar\_main.xml
包含AppBar、content\_main.xml和FAB

NavHostFragment
AppBar以下部分界面