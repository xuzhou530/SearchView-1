# SearchView
This a view that waiting for network connection to resolve with cool animation .
This is an implementation of [this in dribbble](https://dribbble.com/shots/2341287-Search)

![screenshot](github.com/liangpengfei/SearchView/raw/master/screenshots/screenshot.gif)

#Usage

XML


		<xhome.uestcfei.com.searchview.SearchView
        android:layout_width="300dp"
        android:id="@+id/search"
        android:layout_centerHorizontal="true"
        android:layout_height="300dp" />

JAVA

		public void stop(View view) {
      		 Log.d(TAG, "stop");
     		 searchView.stopSearch();
   		 }

   		 public void start(View view) {
     	     Log.d(TAG, "start");
     		 searchView.startSearch();
    	 }