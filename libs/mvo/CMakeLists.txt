INCLUDE_DIRECTORIES("${OPENMVO_SOURCE_DIR}/3rdparty/fast/include")
INCLUDE_DIRECTORIES("${OPENMVO_SOURCE_DIR}/3rdparty/sophus/include")
#���ӱ���ָ��
ADD_DEFINITIONS(-D__SSE2__)#����SSE2
#---------------------------------------------
# Macro declared in "DeclareOPENMVOLib.cmake":
#---------------------------------------------
define_openmvo_lib(
	# Lib name
	mvo 		
	# Dependencies
	openmvo_base
	)
