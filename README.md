<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Maintenance Demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <link href="./custom.css" rel="stylesheet">
</head>
<body>
    <div class="container singleCol">
        <h1>Contact Us</h1>
        <form
            action="https://api.web3forms.com/submit" method="POST">
            <input type="hidden" name="access_key" value="f6654c7e-5f3d-4da6-982f-ff3903e0ad48">
            <input
                type="hidden"
                name="subject"
                value="New Maintenance Request Submission"
            >
            <input
                type="hidden"
                name="name" value="Preston Bennett" >

            <div class="row g-3"> <div class="col-lg-6"> <label for="firstName" class="form-label"> First Name
                    </label>
                <input
                    type="text"
                    class="form-control"
                    id="firstName"
                    aria-describedby="firstName"
                    name="First Name"
                    required
                    >
                </div>
                <div class="col-lg-6"><label for="lastName" class="form-label">
                            Last Name
                       </label>
                    <input
                    type="text"
                    class="form-control"
                    id="lastName"
                    aria-describedby="lastName"
                    name="Last Name"
                    required
                    >
                </div>
                <div class="col-lg-5">
                    <label for="phoneNumber" class="form-label">
                        Phone Number
                    </label>
                    <input
                    type="text"
                    class="form-control"
                    id="phoneNumber"
                    aria-describedby="phoneNumber"
                    name="Phone Number"
                    >
                    <div class="form-text">
                        Please include your area code.
                    </div>
                </div>
                <div class="col-lg-7">
                    <label for="email" class="form-label">
                        E-mail Address
                    </label>
                    <input
                    type="email"
                    class="form-control"
                    id="email"
                    aria-describedby="email"
                    name="Email"
                    >
                </div>

                <div class="col-12">
                    <label for="address" class="form-label">
                        Address
                    </label>
                    <input
                        type="text"
                        class="form-control"
                        id="address"
                        aria-describedby="address"
                        name="Address"
                        required
                    >
                </div>
                <div class="col-md-4">
                    <label for="aptNumber" class="form-label">
                        Apt/Unit # (Optional)
                    </label>
                    <input
                        type="text"
                        class="form-control"
                        id="aptNumber"
                        aria-describedby="aptNumber"
                        name="Apt Number"
                    >
                </div>
                <div class="col-md-8">
                    <label for="dateOfIssue" class="form-label">
                        Date Issue Occurred
                    </label>
                    <input
                        type="date"
                        class="form-control"
                        id="dateOfIssue"
                        name="Date of Issue"
                        required
                    >
                </div>

                <div class="col-12">
                    <label for="moreInformation" class="form-label">
                        Issue or Request
                    </label>
                    <textarea
                    class="form-control"
                    name="More Information" id="More Information" rows="3"
                    required
                    ></textarea>
                </div>
            </div>
            <button type="submit" class="btn btn-outline-dark mt-3">
                Submit Request
            </button>
        </form>
        </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
</body>
</html>
