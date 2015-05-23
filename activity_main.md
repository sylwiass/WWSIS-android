<TableLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    tools:context=".MainActivity"
    android:background="@drawable/pink">
    <TableRow
        android:layout_width="fill_parent"
        android:layout_height="fill_parent">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="3"
            android:gravity="center_horizontal"
            android:textAppearance="?android:attr/textAppearanceLarge"
            android:text="Wpisz kwotę w PLN"
            android:id="@+id/textViewWriten"
            />
    </TableRow>
    <TableRow
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:layout_marginTop="20dp">

        <EditText
            android:id="@+id/text2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:layout_span="1"
            android:layout_weight="1"
            android:inputType="number"
            android:ems="10"/>

        <!--<TextView-->
            <!--android:id="@+id/text1"-->
            <!--android:layout_width="wrap_content"-->
            <!--android:layout_height="wrap_content"-->
            <!--android:layout_column="1"-->
            <!--android:layout_span="1"-->
            <!--android:layout_weight="1"-->
            <!--android:text="PLN" />-->


    </TableRow>
<TableRow
    android:layout_width="fill_parent"
    android:layout_height="fill_parent"
    android:layout_marginTop="20dp">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="3"
            android:gravity="center_horizontal"
            android:textAppearance="?android:attr/textAppearanceLarge"
            android:text="Wybierz walutę"
            android:id="@+id/textViewChoose"
            />
</TableRow>
        <TableRow
            android:layout_width="fill_parent"
            android:layout_height="fill_parent"
            android:layout_marginTop="20dp">
        <Spinner
            android:id="@+id/first"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_column="0"
            android:layout_span="1"
            android:layout_weight="1"/>
        <!--<Spinner-->
            <!--android:id="@+id/second"-->
            <!--android:layout_width="wrap_content"-->
            <!--android:layout_height="wrap_content"-->
            <!--android:layout_column="1"-->
            <!--android:layout_span="1"-->
            <!--android:layout_weight="1"/>-->
        </TableRow>

    <TableRow
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:layout_marginTop="50dp">

        <Button
            android:id="@+id/count"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="3"
            android:text="PRZELICZ"
           />
        </TableRow>
    <TableRow
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:layout_marginTop="20dp">

    <TextView
        android:id="@+id/text3"
        android:layout_width="fill_parent"
        android:layout_height="50dp"
        android:layout_column="0"
        android:layout_span="1"
        android:layout_weight="1"
        android:gravity="center"
        android:text="" />
    </TableRow>
</TableLayout>

