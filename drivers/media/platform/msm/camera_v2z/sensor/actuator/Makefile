ccflags-y += -Idrivers/media/platform/msm/camera_v2z
ccflags-y += -Idrivers/media/platform/msm/camera_v2z/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2z/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2z/sensor/cci
obj-$(CONFIG_ZUK_CAMERA) += msm_actuator.o

CFLAGS_msm_actuator.o += $(call cc-disable-warning, enum-conversion)