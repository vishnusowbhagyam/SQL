- Constraints are used to set a certain rules to the column or table. The constraints can restrict the type of data that can be inserted or updated in particular column.
- This helps you to maintain the data accuracy and data consistency in the table. There are two types of constraints:
- Syntax:
  Create table table_name(
    col1 datatype constraint,
                              -- column level constraints
    col2 datatype constraint,
    .......
    .......
    constraint(col_name)   -- Table level constraints
  );
  -- column level constraints
  This type of costraints will only applied to a column in the table.
  -- Table level constraints:
  This contraints will apply to the complete table.
   -- Types of constraints:
  1. Not null:
  This constraint indicates that no column cannot store the null values or blank values
  2. Unique :
     This contraint indicates that column only have unique values like a value stores only once in a column same like null value also.
  3. Primary Key:
     This constraint is a combination of Not null and Unique and this is only ones in a table.
  4. Foriegn Key:
     This constraint is used when we have 2 or more columns and indicates it as a connecting column to the tables.
  5. Check :
     This constraint indicates that the values in a columns can only allows if the condition is satisfied.
  6. Default:
     This constraint provides a default value for a column if no value is explicitly specified during an insert operation
  7. Auto Increment:
     This constraint automatically generates a unique numbers when a record is entered into the table.
     
