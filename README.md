# Definition-2
Write a PL/SQL block which converts temperature from Celsius to Fahrenheit.
set serveroutput on;

declare

    v_celsius     number;

    v_fahrenheit  number;

begin
    
    v_celsius := &enter_celsius;
    v_fahrenheit := (v_celsius * 9/5) + 32;

    dbms_output.put_line('temperature in celsius : ' || v_celsius);
    dbms_output.put_line('temperature in fahrenheit : ' || v_fahrenheit);

end;
/

