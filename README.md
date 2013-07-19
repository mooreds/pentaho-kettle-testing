This contains Pentaho Kettle transforms and jobs to illustrate testing practices for this ETL tool.

Read the companion blog posts, starting at http://www.mooreds.com/wordpress/archives/995

Note that if you are running this on unix, you may need to convert the input files to dos format, using [dos2unix](http://www.linuxcommand.org/man_pages/dos2unix1.html).

You'll also want to set up a repository pointing to the `repository` subdirectory, in your `.kettle/repositories.xml` 

    <repository>    
    <id>KettleFileRepository</id>
    <name>testing</name> 
    <description>Testing</description>
    <base_directory>/path/to/your/repository/</base_directory>
    <read_only>N</read_only>
    <hides_hidden_files>N</hides_hidden_files>
    </repository>  
