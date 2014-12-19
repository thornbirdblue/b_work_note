PD1303:

02-12
正在发送       QCamera2HWICallbacks.cpp
传输文件数据 .
提交后的版本为 14610。
dumpdata from data to sdcard!

02-28
正在发送       QCamera2HWI.cpp
正在发送       QCamera2HWICallbacks.cpp
正在发送       QCameraParameters.cpp
传输文件数据 ...
提交后的版本为 15664。
close hal log

03-21
正在发送       isp.c
传输文件数据 .
提交后的版本为 17642。
[PD1303]:[B140225-151]（ANR）进入专业相机，点击拍照按钮后立即滑动调焦按钮到最左端，提示“很抱歉，相机已停止运行”。（6次/10次）

04-07
正在发送       QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 19222。
[PD1303LG3]: getExifData add log for [B140320-171]

04-09
正在发送       port_sensor.c
传输文件数据 .
提交后的版本为 19387。
[PD1303A]: add AEC log of flash for [B140327-049] [B140329-173]

正在发送       msm_sensor.c
传输文件数据 .
提交后的版本为 19449。
[PD1303LG3]: Camera driver read sensor id that can read 3 times![B140409-252]MTBF：打开相机，提示相机故障，无法连接到相机。时间04-05 05：58

04-10
增加           camera
增加           camera/camera.c
传输文件数据 .
提交后的版本为 19551。

camera open and close add wakelock!

增加           pproc_port.c
传输文件数据 .
提交后的版本为 19607。
[PD1303A]: pproc_port_sink_check_caps_reserve add error log for [B140301-036]（anr）锁屏界面左滑动进入相机，滑动背键拍照提示：相机停止运行（1/次20次）

04-18
正在发送       QCamera2HWICallbacks.cpp
传输文件数据 .
提交后的版本为 20272。
PD1303A: Failed to config stream rc = -1. case:01505232 

04-21
正在发送       QCamera2HWICallbacks.cpp
正在发送       QCameraParameters.cpp
传输文件数据 ..
提交后的版本为 20566。
PD1303A: revert 20272 modify and add getExif error log

04-25
正在发送       QCamera2HWI.cpp
正在发送       QCamera2HWI.h
传输文件数据 ..
提交后的版本为 21432。
PD1303LG3:[B140320-064]（ANR）设置不同视频大小、开/关水印录像并拍照后提示“相机已停止运行”（1次/20次）
          https://www.codeaurora.org/cgit/external/gigabyte/platform/hardware/qcom/camera/commit/?h=caf/kk_3.5_rb2.10&id=2ae46a9f85ade5db335eae088f8b57ecbfff99ba

04-29
正在发送       camera.c
传输文件数据 .
提交后的版本为 21794。
[B140426-132](死机）使用易信软件与另一台手机建立通话，结束后出现黑屏死机(1/20)  wakelock

05-06
正在发送       QCameraParameters.cpp
传输文件数据 .
提交后的版本为 22531。
[PD1303]:correct lookupAttr error of qcom platform!
                  /system/lib/hw/camera.msm8974.so (qcamera::QCameraParameters::lookupAttr(qcamera::QCameraParameters::QCameraMap const*, int, char const*)+24)
[B140506-211]相机连续拍照会出现/system/lib/hw/camera.msm8974.so (qcamera::QCameraParameters::lookupAttr(qcamera::QCameraParameters::QCameraMap const*, int, char const*)+24)

05-10
正在发送       camera.c
传输文件数据 .
提交后的版本为 23116。
[PD1303]: delete camera open wakelock for
         [B140506-205]（重启）微信：点击微信运行手机重启/死机（5次/5次）
        [B140509-091]手机拍照后，退出相机后台进入省电，底电流降不下来，为11.6ma

07-22
正在发送       QCameraMem.cpp
传输文件数据 .
提交后的版本为 1973。
tag:patch:PD1303 close QCameraHWI_Mem log

正在发送       QCamera2HWI.cpp
正在发送       QCameraParameters.cpp
传输文件数据 ..
提交后的版本为 31043。
[PD1303A]:close HWI parameters log

正在发送       liteon_13p1bca_eeprom.c
传输文件数据 .
提交后的版本为 31047。
[PD1303]: close eeprom log

08-12
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 .
提交后的版本为 33893。
PD1303: commit new stats_algorithm lib of del mm-camera-CORE log

08-22
正在发送       msm_buf_mgr.c
传输文件数据 .
提交后的版本为 2160。
tag:patch:PD1303/PD1302 case 01616809 ION release error cause system reboot


06-06
正在发送       sensor.c
传输文件数据 .
提交后的版本为 25977。
[PD1303LG3]: qcom patch: correct mm-camera-sensor: sensor_apply_exposure:527 failed

正在发送       ov13850_lib.c
传输文件数据 .
提交后的版本为 26018。
[PD1303LG3]: add 30fps op clk to 600 for vfe overflow! (qcom patch)

06-25
正在发送       sensor.c
传输文件数据 .
提交后的版本为 27850。
[PD1303LG3]: comment sensor_set_resolution() repeate SENSOR CFG
             [B140620-030]（ANR）MTBF：进入相机，点击拍照时提示“相机”已停止运行。（1次/20次）


正在发送       msm_cci.c
传输文件数据 .
提交后的版本为 27851。
[PD1303LG3]: Modify cci wirte timeout from 100ms to 200ms
             [B140620-030]（ANR）MTBF：进入相机，点击拍照时提示“相机”已停止运行。（1次/20次）

06-27
ats/q3a$ svn ci q3a_port.c
正在发送       q3a_port.c
传输文件数据 .
提交后的版本为 28194。
[PD1303LG3]: prepare snapshot hang error!
             [B140627-327]进入相机切换POSE模式下反复开关闪光灯拍照提示相机停止运行（1次20次）

07-04
正在发送       mct_stream.c
增加           mct_stream.h
传输文件数据 ..
提交后的版本为 28838。
[PD1303LG3]: add qcom patch 0001-mm-camera2-fix-caching-prepare-snapsht-done-bug-msg-.patch
            [B140627-327]进入相机切换POSE模式下反复开关闪光灯拍照提示相机停止运行（1次20次）

07-15
正在发送       QCameraParameters.cpp
传输文件数据 .
提交后的版本为 30222。
[PD1303LG3]: correct Thumbnail size is error!

07-18
正在发送       msm_buf_mgr.c
正在发送       msm_buf_mgr.h
传输文件数据 ..
提交后的版本为 1951。
bbkpatch.shc commit msm_buf_mgr.h msm_buf_mgr.c -m "tag:patch:PD1303LG3 case 01616809 ION release error cause system reboot"
PD1302 product line:


pd1302
04-20
正在发送       QCamera2HWICallbacks.cpp
传输文件数据 .
提交后的版本为 20510。
[PD1302]: Failed to config stream rc = -1. [B140411-334]（进入相机后）从前置摄像头切换为后置，再次切换到夜景模式后按拍照键提示相机停止运行。（2次/20次）

04-24
正在发送       QCamera2HWICallbacks.cpp
传输文件数据 .
提交后的版本为 21163。
[PD1302]:revert r20510 for Failed to config stream

05-03
正在发送       QCameraParameters.cpp
传输文件数据 .
提交后的版本为 22002。
[PD1302]: [B140412-357]【功能异常】从便签进入相机点击多次拍照无作用。（1次/20次）
[B140420-283]（anr）进入相机HDR模式进行拍照，在切换到摄像模式点击停止键提示相机停止运行；（1次/20次）

正在发送       QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 22003。

[PD1302]: qcom patch:when flash is on,precapture is not return AEC event in takePicture!

05-05
正在发送       vendor/vivo/overlay/project/PD1302/hardware/qcom/camera/QCamera2/HAL/QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 22399。
PD1302]: hdr capture,then turn to zsl mode, AE lock! 0001-QCamera2-disable-AEBracket-when-switch-to-zsl-mode.patch

正在发送       QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 22528。

PD1302:patch hdr_flash_issue.patch

正在发送       QCameraParameters.cpp
传输文件数据 .
提交后的版本为 22529。
PD1302: 0001-QCamera2-fix-the-mistake-type-of-getFlashValue
/system/lib/hw/camera.msm8974.so (qcamera::QCameraParameters::lookupAttr 
/system/lib/hw/camera.msm8974.so (qcamera::QCamera2HardwareInterface::getExifData()+84
[B140424-078]（anr）在正常模式下长按连拍按钮提示无法连接到相机。（1次/20次）

05-21
正在发送       colorcorrect40.c
传输文件数据 .
提交后的版本为 24291。
[PD1302]: close util_set_color_correction_params log!


06-23
正在发送       sensor.c
传输文件数据 .
提交后的版本为 27604。
[PD1302]: [B140622-188]（死机）进入相机设置视频大小为4K进入专业模式摄像，手机死机。

06-24
正在发送       libmmcamera2_frame_algorithm.so
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 ..
提交后的版本为 27691。
[B140603-129](anr)进入相机，开启闪光灯，切换到自动场景模式，在暗环境下识别后拍照，再移置正常环境下识别后拍照，出现“很抱歉，相机已停止运行”等字样（1/20）

正在发送       pproc_port.c
传输文件数据 .
提交后的版本为 27705。
[B140609-100]（内部试用）拍照按钮无作用

06-25
正在发送       pproc_port.c
传输文件数据 .
提交后的版本为 27806。
	port_stream_info->stream_info = NULL; 

正在发送       sensor.c
传输文件数据 .
提交后的版本为 27853。
[PD1302L]:comment sensor_set_resolution() repeat reg set
          [B140612-418](anr)在相册对图片进行任意编辑后home返回桌面，进入相机，连拍十多张，锁屏，解锁后home返回桌面，点击相册进入，弹出：相册已停止运行（2/20）

06-26
正在发送       mm_camera_channel.c
传输文件数据 .
提交后的版本为 27969。
[PD1302l]:HAL's stopPreview is not execute finish.
          [B140625-112]使用一键加速结束相机，锁屏，插旅充充电再解锁进入相机，提示相机故障。（1次/20次）

06-28
正在发送       q3a_port.c
传输文件数据 .
提交后的版本为 28217。
[PD1302L]: qcom patch prepare snapshot question!
           [B140623-125]（内部试用）手机拍照用专业拍照模式，拍照中显示“无法连接到相机”

07-01
正在发送       bus/mct_bus.c
正在发送       stream/mct_stream.c
传输文件数据 ..
提交后的版本为 28418。
[PD1302]: [B140621-043]专业相机，开启闪光灯拍照几张后向上滑动，提示相机故障，无法连接到相机（1/20）

08-05
正在发送       QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 32930。
[PD1302L]:Livesnapshot use hw rotation.not use sw!


08-09
正在发送       mct_stream.c
正在发送       mct_stream.h
传输文件数据 ..
提交后的版本为 33584。
PD1302: prepare error for resolve, sync  with PD1303
		[B140802-100]相机中，开启闪光灯，切换到自动场景模式，识别到夜景后拍照，再切换到正常模式，点击拍照，相机界面卡死，稍后提示无法连接到相机。(3/20)

PD1302LG4
正在发送       QCamera2HWI.cpp
传输文件数据 .
提交后的版本为 23597。
[PD1302LG4]: when flash is on,precapture is not return AEC event in takePicture!
              [B140512-182]（ANR）进入相机，在各模式之间进行切换拍照，弹出相机停止运行。（1次/20次）

正在发送       msm_sensor.c
传输文件数据 .
提交后的版本为 24406。
[PD1302LG4]:[B140519-131]MTBF：打开相机，提示相机故障，无法连接到相机。时间04-05 05：58


正在发送       mm-camera2/media-controller/mct/bus/mct_bus.c
正在发送       mm-camera2/media-controller/modules/stats/stats_port.c
传输文件数据 ..
提交后的版本为 24435。

06-07
正在发送       QCameraParameters.cpp
传输文件数据 .
提交后的版本为 26124。
[PD1302]:correct thumbnail size is error!
         [B140603-399]【产线反馈】相机界面触摸屏幕无作用、按back键无作用，按Home键退出相机再进入恢复正常

06-09
正在发送       QCameraPostProc.cpp
传输文件数据 .
提交后的版本为 26266。
[PD1302L]: add error log for cpp doreprocess error!

06-30
正在发送       q3a_port.c
传输文件数据 .
提交后的版本为 28297。
[B140610-223]进入*#558#中关闭各种log，再进入文件管理中清除log，重启手机后，再开启log，然后进入相机，出现"相机故障，无法连接到相机"(1/20)

07-31
正在发送       QCameraPostProc.cpp
传输文件数据 .
提交后的版本为 32381。
[PD1302]:correct ISO value
         [B140519-175]夜晚拍照后，查看照片详细信息，ISO和曝光时间异常，ISO为2万多，曝光时间为十亿分之一（1/20）

正在发送       QCameraStateMachine.cpp
传输文件数据 .
提交后的版本为 32401。
[PD1302]: [B140725-021]monkey test：相机异常ANR，子类型/详细信息：keyDispatchingTimedOut/时间无响应

09-09
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 .
提交后的版本为 36916。
PD1302:close mm-camera-CORE LOG in algo


PD1302F
07-15
正在发送       libmmcamera2_frame_algorithm.so
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 ..
提交后的版本为 30320。
[PD1302F]:sync with PD1302L lib!

09-09
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 .
提交后的版本为 36923。
PD1302F:close mm-camera-CORE LOG in algo

PD1302F_EX
07-15
正在发送       libmmcamera2_frame_algorithm.so
正在发送       libmmcamera2_stats_algorithm.so
传输文件数据 ..
提交后的版本为 30324。
