# Homework 1: Horiseon's Refactor

This is a refactoring for the company Horiseon. They wanted their site to be acessiable to readers to translate imformation from their site to audio.

## Before
    This file had many <div> tages with classes with its' labels.
    Here's an example below of the html line and CSS to match.

    '''
    <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>
    
    footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    }
    
    '''
## After 
However the class says footer when it could be the tag footer and changing the CSS sheet to match.

    '''
    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>

    footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    }
    '''
    
## Contributors
    
Horiseon: Owner of files

Stephen Fink: Refactor