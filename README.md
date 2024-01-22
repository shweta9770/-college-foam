<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOAM</title>
</head>
<body>
    <h2>Enquery</h2>
    <form>
        <fieldset>
            <legend> COLLEGE FOAM </legend>
        Name: <input type="text" name="name" value="" 
        placeholder="enter Name"> 
        <br/>
        <br/>
        Adress: <textarea name="Adress"></textarea>
        <br/>
        <br/>
        gender: 
        <input type="radio" value="m" name="gender"/> male 
        <input type="radio" value="f" name="gender"/>female 
        <input type="radio" value="o" name="gender"/>other
        <br/>
        <br/>
        country:
        <select>
            <optgroup label="asia">
                <option>please select country</option>
            <option value="india">india</option>
            <option value="india">india</option>

            </optgroup>
            
            <option value="usa">india</option>
        </select>
        <br/>
        <br/>
        hobbies:
        <input type="checkbox" name="">dancing
        <input type="checkbox" name="">singing
        <br/>
        <br/>
        image:
        <input type="file" name="image"/>
        <input type="submit" value="send"/>
        <input type="reset" value="reset"/>
    </fieldset>

    </form>
</body>
</html>
