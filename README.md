# SimplePremissionCheck
call constructor with passing arguments context and needed permission 

     val neededpermission = arrayOf(android.Manifest.permission.ACCESS_COARSE_LOCATION,
     android.Manifest.permission.ACCESS_FINE_LOCATION,
     android.Manifest.permission.CAMERA,
     android.Manifest.permission.RECORD_AUDIO)
     
MultiplePermissionsActivity(context,neededpermission)
