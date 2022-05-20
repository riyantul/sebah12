<template>
    <div class="container my-5">
        <div class="row justify-content-center">
            <div class="col-xl-6 col-sm-8">
                <!-- <router-link :to="{ name: 'transaction.create' }"
                class="btn btn-primary btn-sm rounded shadow mb-3"
                >Add</router-link> -->
                <div class="card rounded shadow">
                    <div class="card-header bg-primary text-white py-3">
                        Login
                    </div>
                    <div class="card-body"> 
                        <form>
                            <div class="mb-3">
                                <label for="exampleInputEmail1" class="form-label">Email address</label>
                                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3">
                                <label for="exampleInputPassword1" class="form-label">Password</label>
                                <input type="password" class="form-control" id="exampleInputPassword1">
                            </div>
                            <button type="submit" class="btn btn-primary">Submit</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script> 
export default { 
    
}
</script>
