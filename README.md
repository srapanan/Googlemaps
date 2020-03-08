!<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
      <div class="container">
        <div class="panel panel-primary">
        <div class="panel-heading">
        <h2 class="panel-title">Add your Address</h2>
      </div>
      <div class="panel-body">
        <input id="autocomplete" placeholder="Enter your address" onFocus="geolocate()" type="text" class="form-control">
        <div id="address">
          <div class="row">
            <div class="col-md-6">
              <label class="control-label">Street address</label>
              <input class="form-control" id="street_number" disabled="true">
            </div>
            <div class="col-md-6">
              <label class="control-label">Route</label>
              <input class="form-control" id="route" disabled="true">
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <label class="control-label">City</label>
              <input class="form-control field" id="locality" disabled="true">
            </div>
            <div class="col-md-6">
              <label class="control-label">State</label>
              <input class="form-control" id="administrative_area_level_1" disabled="true">
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <label class="control-label">Zip code</label>
              <input class="form-control" id="postal_code" disabled="true">
            </div>
            <div class="col-md-6">
              <label class="control-label">Country</label>
              <input class="form-control" id="country" disabled="true">
            </div>
          </div>
        </div>
      </div>
    </div>
</div>
  <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAcIGfYDMu8bU9i663-ooSTVpOEP3vV8O4&libraries=places&callback=initAutocomplete" async defer></script>
  </body>
</html>
