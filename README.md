# learn-APIClound
##Method——方法API
1. api.require("");——引用模块；
2. api.openVideo({params})——打开系统视频播放器
3. api.stopPlay();——停止播放音频 
3. api.startPlay({params},callback(ret,err));——播放本地音频，支持amr格式
3. api.stopRecord(callback(ret,err)); ——停止录音
3. api.startRecord({params});——录制amr格式音频
3. api.saveMediaToAlbum({param},callback(ret,err));——保存图片和视频到系统相册
3. api.getPicture({},callbackf(ret,err));
3. api.showFloatBox({params},callback);——显示一个悬浮框，浮动在屏幕上。
3. api.refreshHeaderLoadDone();——通知顶部刷新数据加载完毕。
3. api.refreshHeaderloading();——通知下拉刷新组件为刷新状态
3. api.setCustomRefreshHeaderInfo()——显示自定义下拉刷新组件。
3. api.setRefreshHeaderInfo();——显示默认下拉刷新组件，使用默认下拉刷新组件时页面必须设置为弹动。
3. api.openPicker({params}，callback);——打开时间选择器
3. api.toast();——弹出一个定时自动关闭的提示框；
3. api.hideProgress();——隐藏提示框
3. api.showProgress();——显示进度提示框
3. api.actionSheet({},callback);——底部弹出框
3. api.prompt();——弹出两个或三个按钮和输入框的对话框。
3. api.confirm();——弹出两个或三个按钮的confirm对话框。
3. api.alert();弹出一个按钮的对话框
3. api.requestPermission();像系统请求某个或多个权限
3. api.haspermission();检测应用是否有某个或多个权限。
3. api.getPhoneNumber();获取本机电话号码，只支持部分Android手机
4. api.setAppIconBadge();设置应用图标右上角数字
5. api.setScreenSecure();设置是否禁止截屏；
6. api.toLauncher();回到系统界面
3. api.setKeepScreenOn();设置是否禁止屏幕休眠；
3. api.setScreenOrientation;设置屏幕旋转方向；
3. api.setStatusBarStyle();设置状态栏样式为白色（适用于深色背景）或黑色（适用于浅色背景），以及设置状态栏背景颜色。
4. setFullScreen();设置是否全屏
5. openContacts;在应用内打开系统通讯界面选择联系人
4. mail;发送邮件；
5. sms;调用系统短信界面发送短信，或者后台直接发送短信
3. call;拨打电话或进行faceTime
3. stopsensor;停止传感器
3. startSensor;开启传感器；
3. getLocation;获取位置信息；
3. stopLocation；停止定位的
3. startLocation 开始定位
3. cancelNotification 取消本应用弹出到状态栏的某个或所有通知，也可以清除设定的闹铃
3. notification 向用户发出震动、声音提醒、灯光闪烁、手机状态通知等提示行为支持闹铃功能
3. accessNative 使用SuperWebView时，js向原生发送消息。
3. sendEvent 将任意一个自定义事件广播出去，该事件可在任意页面通过add Event Listener监听收到
4. removeEventListener移除事件监听
5. addEventListener;监听事件，支持系统事件和自定义事件













