<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.bob.interfaceadmin.MainActivity"
    tools:layout_editor_absoluteY="81dp"
    tools:layout_editor_absoluteX="0dp">

    <ExpandableListView
        android:layout_width="365dp"
        android:layout_height="420dp"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="8dp"
        tools:layout_editor_absoluteY="51dp" />

    <EditText
        android:id="@+id/editText"
        style="@style/Base.AlertDialog.AppCompat.Light"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="text|textPersonName"
        android:text="Liste des signalements"
        tools:ignore="HardcodedText,MissingConstraints"
        tools:layout_editor_absoluteX="110dp"
        tools:layout_editor_absoluteY="5dp" />
</android.support.constraint.ConstraintLayout>

