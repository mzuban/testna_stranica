<template>
    <div class="about">
        <h1>This is a login page</h1>
  
        <div class="row">
            <div class="col"></div>
            <div class="col">
                <form>
                    <div class="form-group">
                        <label for="exampleInputName">Ime</label>
                        <input type="name" class="form-control" id="exampleInputName" placeholder="Name" />
                    </div>
                    <div class="form-group">
                        <label for="exampleInputSurname">Prezime</label>
                        <input type="surname" class="form-control" id="exampleInputSurname" placeholder="Surname" />
                    </div>
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email adresa*</label>
                        <input
                            type="email"
                            class="form-control"
                            id="exampleInputEmail1"
                            aria-describedby="emailHelp"
                            placeholder="Enter email"
                        />
                        <small id="emailHelp" class="form-text text-muted">
                            *We'll never share your email with anyone else.
                        </small>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password*</label>
                        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password" />
                        <small id="emailHelp" class="form-text text-muted">
                            *We'll never share your password with anyone else.
                        </small>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
            <div class="col"></div>
        </div>
    </div>
  </template>