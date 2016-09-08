Route::group(['namespace' => 'Admin\Location','prefix' => 'Admin/Location','middleware'=>['web','auth']], function()
  {
// Controllers Within The "App\Http\Controllers\Dashboard" Namespace

    Route::group(['namespace' => 'Region','prefix' => 'Region'], function() {
    // Controllers Within The "App\Http\Controllers\Dashboard\LiveStats" Namespace
         Route::get('/', 'RegionController@index');
          Route::get('create',['uses' => 'RegionController@create']);
          Route::post('save',['uses' => 'RegionController@store']);     
        
    });

    //Region-stats
   
  });
