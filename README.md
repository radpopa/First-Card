# First-Card
Project Udacity


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.draculacastle.FirstcardActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/draculacastle"
        android:scaleType="centerCrop"
        />
    <TextView android:text="Greetings from Dracula Castle! "
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="36sp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:padding="20dp">

    </TextView>

    <TextView android:text=" Radu "
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:textSize="36sp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:padding="20dp"
        />

</RelativeLayout>
